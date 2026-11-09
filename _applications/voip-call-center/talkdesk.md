---
app: Talkdesk
app_slug: talkdesk
app_url: https://www.talkdesk.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430.30.10
  key: BC-430.30.10
  layer: domain
  name: Contact Centre Workforce Management
  providers:
  - Verint (WFM Cloud)
  url: /capabilities/contact-centre-operations-management/
  via_parent: Contact Centre Operations Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Keap
  - Microsoft Dynamics 365
  - Pipedrive
  - Salesforce
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
  - Help Scout
  - Intercom
  - Kustomer
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2900.60
  key: BC-2900.60
  layer: domain
  name: Healthcare Interoperability Operations
  providers:
  - athenahealth
  - Epic
  - Oracle Cerner
  url: /capabilities/healthcare-interoperability-operations/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: domain
  name: IT Service Management
  providers:
  - ServiceNow
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2160
  key: insurance-claims-management
  layer: domain
  name: Insurance Claims Management
  providers:
  - Guidewire ClaimCenter
  url: /capabilities/insurance-claims-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: domain
  name: Programmable Voice
  providers:
  - Zoom Phone
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: Turbo EA
  id: BC-410
  key: sales-management
  layer: domain
  name: Sales Management
  providers:
  - Outreach
  url: /capabilities/sales-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Contacts
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
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
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Workato
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: voip-call-center
  name: VoIP, Phone & Contact Center
  url: /applications/voip-call-center/
counts:
  declared: 25
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.talkdesk.com/integrations/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: BC-2900.60
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.9
    band: exemplar
    in_catalog: true
    kin_score: 67.0
    mcp: &id001
      status: none
    slug: athenahealth
    status: profiled
    tags: &id002
    - Electronic Health Records
    - Healthcare
    - Practice Management
    - Revenue Cycle Management
    url: /providers/athenahealth/
  layer: domain
  name: athenahealth
  provider: athenahealth
  says: lists athenahealth as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: BC-2900.60
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id003
      status: none
    slug: epic-systems
    status: profiled
    tags: &id004
    - Electronic Health Records
    - FHIR
    - Healthcare
    - United States
    url: /providers/epic-systems/
  layer: domain
  name: Epic
  provider: epic-systems
  says: lists Epic as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id005
      status: none
    slug: freshdesk
    status: profiled
    tags: &id006
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id007
      source: https://dev.frontapp.com/docs/mcp
      status: documented
    slug: front
    status: profiled
    tags: &id008
    - Customer Operations
    - Customer Service
    - Email
    - Inbox
    url: /providers/front/
  layer: domain
  name: Front
  provider: front
  says: lists Front as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id009
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-people
    status: profiled
    tags: &id010
    - Address Book
    - Contacts
    - Google
    - People
    url: /providers/google-people/
  layer: common
  name: Google Contacts
  provider: google-people
  says: lists Google Contacts as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2160
    key: insurance-claims-management
    name: Insurance Claims Management
    url: /capabilities/insurance-claims-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.0
    band: strong
    in_catalog: true
    kin_score: 63.6
    mcp: &id011
      status: none
    slug: guidewire
    status: profiled
    tags: &id012
    - Billing
    - Claims
    - Insurance
    - Policy
    url: /providers/guidewire/
  layer: domain
  name: Guidewire ClaimCenter
  provider: guidewire
  says: lists Guidewire ClaimCenter as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id013
      status: none
    slug: helpscout
    status: profiled
    tags: &id014
    - Customer Service
    - Email
    - Help Desk
    - Live Chat
    url: /providers/helpscout/
  layer: domain
  name: Help Scout
  provider: helpscout
  says: lists Help Scout as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id015
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id016
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id017
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom
  provider: intercom
  says: lists Intercom as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id019
      status: none
    slug: keap
    status: profiled
    tags: &id020
    - CRM
    - Marketing Automation
    - Sales
    - Small Business
    url: /providers/keap/
  layer: domain
  name: Keap
  provider: keap
  says: lists Keap as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id021
      status: none
    slug: kustomer
    status: profiled
    tags: &id022
    - CRM
    - Customer Service
    - Help Desk
    - Messaging
    url: /providers/kustomer/
  layer: domain
  name: Kustomer
  provider: kustomer
  says: lists Kustomer as an integration
  source: https://www.talkdesk.com/integrations/
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
    agent_readiness: 33.1
    band: strong
    in_catalog: true
    kin_score: 63.9
    mcp: &id023
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id024
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics 365
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics 365 as an integration
  source: https://www.talkdesk.com/integrations/
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id025
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id026
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2900.60
    key: BC-2900.60
    name: Healthcare Interoperability Operations
    url: /capabilities/healthcare-interoperability-operations/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id027
      status: none
    slug: oracle-health
    status: profiled
    tags: &id028
    - Bulk FHIR
    - CapabilityStatement
    - CareAware
    - Cerner Millennium
    url: /providers/oracle-health/
  layer: domain
  name: Oracle Cerner
  provider: oracle-health
  says: lists Oracle Cerner as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id029
      status: none
    slug: outreach
    status: profiled
    tags: &id030
    - CRM
    - Sales
    - Sales Engagement
    - Sequences
    url: /providers/outreach/
  layer: domain
  name: Outreach
  provider: outreach
  says: lists Outreach as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id031
      status: none
    slug: pipedrive
    status: profiled
    tags: &id032
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id033
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id034
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id035
      status: none
    slug: servicenow
    status: profiled
    tags: &id036
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: domain
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id037
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id038
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-430.30.10
    key: BC-430.30.10
    name: Contact Centre Workforce Management
    url: /capabilities/contact-centre-operations-management/
    via_parent: Contact Centre Operations Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 8.8
    mcp: &id039
      status: none
    slug: verint-systems
    status: profiled
    tags: &id040
    - Analytics
    - Customer Engagement
    - Security
    url: /providers/verint-systems/
  layer: domain
  name: Verint (WFM Cloud)
  provider: verint-systems
  says: lists Verint (WFM Cloud) as an integration
  source: https://www.talkdesk.com/integrations/
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
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id041
      source: https://docs.workato.com/mcp.html
      status: verified
    slug: workato
    status: profiled
    tags: &id042
    - AI Agents
    - API Management
    - Automation
    - B2B
    url: /providers/workato/
  layer: common
  name: Workato
  provider: workato
  says: lists Workato as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id043
      status: none
    slug: zendesk
    status: profiled
    tags: &id044
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.talkdesk.com/integrations/
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
    mcp: &id045
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id046
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://www.talkdesk.com/integrations/
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
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id047
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id048
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: exemplar
    in_catalog: true
    kin_score: 69.5
    mcp: &id049
      status: none
    slug: zoom-phone
    status: profiled
    tags: &id050
    - Cloud PBX
    - Telecommunications
    - UCaaS
    - United States
    url: /providers/zoom-phone/
  layer: domain
  name: Zoom Phone
  provider: zoom-phone
  says: lists Zoom Phone as an integration
  source: https://www.talkdesk.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/voip-call-center/talkdesk/
providers:
- agent_band: agent-ready
  agent_readiness: 30.9
  band: exemplar
  in_catalog: true
  kin_score: 67.0
  mcp: *id001
  name: athenahealth
  slug: athenahealth
  status: profiled
  tags: *id002
  url: /providers/athenahealth/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id003
  name: Epic
  slug: epic-systems
  status: profiled
  tags: *id004
  url: /providers/epic-systems/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id005
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id006
  url: /providers/freshdesk/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id007
  name: Front
  slug: front
  status: profiled
  tags: *id008
  url: /providers/front/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id009
  name: Google Contacts
  slug: google-people
  status: profiled
  tags: *id010
  url: /providers/google-people/
- agent_band: agent-native
  agent_readiness: 42.0
  band: strong
  in_catalog: true
  kin_score: 63.6
  mcp: *id011
  name: Guidewire ClaimCenter
  slug: guidewire
  status: profiled
  tags: *id012
  url: /providers/guidewire/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id013
  name: Help Scout
  slug: helpscout
  status: profiled
  tags: *id014
  url: /providers/helpscout/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id015
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id016
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id017
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id018
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 45.4
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id019
  name: Keap
  slug: keap
  status: profiled
  tags: *id020
  url: /providers/keap/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 25.6
  mcp: *id021
  name: Kustomer
  slug: kustomer
  status: profiled
  tags: *id022
  url: /providers/kustomer/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id023
  name: Microsoft Dynamics 365
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id024
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id025
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id026
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id027
  name: Oracle Cerner
  slug: oracle-health
  status: profiled
  tags: *id028
  url: /providers/oracle-health/
- agent_band: agent-ready
  agent_readiness: 53.1
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id029
  name: Outreach
  slug: outreach
  status: profiled
  tags: *id030
  url: /providers/outreach/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id031
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id032
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id033
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id034
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id035
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id036
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id037
  name: Slack
  slug: slack
  status: profiled
  tags: *id038
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 8.8
  mcp: *id039
  name: Verint (WFM Cloud)
  slug: verint-systems
  status: profiled
  tags: *id040
  url: /providers/verint-systems/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id041
  name: Workato
  slug: workato
  status: profiled
  tags: *id042
  url: /providers/workato/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id043
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id044
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 86.0
  mcp: *id045
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id046
  url: /providers/zoho-crm/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id047
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id048
  url: /providers/zoom/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 69.5
  mcp: *id049
  name: Zoom Phone
  slug: zoom-phone
  status: profiled
  tags: *id050
  url: /providers/zoom-phone/
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
- name: JustCall
  rows: 36
  url: /applications/voip-call-center/justcall/
sitemap: true
title: 'Talkdesk: VoIP, Phone & Contact Center reference app'
---
