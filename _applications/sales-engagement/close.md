---
app: Close
app_slug: close
app_url: https://www.close.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Help Scout
  - Missive
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: domain
  name: Data Enrichment
  providers:
  - Clay
  - Findymail
  - UpLead
  - Voila Norbert
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Customer.io
  - Drip
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Google Calendar
  - Microsoft 365
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
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
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: domain
  name: Scheduling & Appointment Management
  providers:
  - Calendly
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: video-calling
  layer: domain
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: voice-telephony
  layer: domain
  name: Voice & Telephony
  providers:
  - JustCall
  - Ringover
  url: /capabilities/voice-telephony/
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
  - Airbyte
  - Fivetran
  - Hightouch
  - Segment
  - Skyvia
  - Stitch
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-931
  key: AE-931
  layer: common
  name: No-Code App Builders
  providers:
  - Retool
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: API Evangelist extension
  id: AE-160.80
  key: qualified-electronic-signatures-trust-services
  layer: common
  name: Qualified Electronic Signatures & Trust Services
  providers:
  - SignWell
  url: /capabilities/qualified-electronic-signatures-trust-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - ChatGPT
  - Claude
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: sales-engagement
  name: Sales Engagement & Dialers
  url: /applications/sales-engagement/
counts:
  declared: 34
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.close.com/integrations
integrations:
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
    agent_readiness: 44.2
    band: exemplar
    in_catalog: true
    kin_score: 77.5
    mcp: &id001
      status: none
    slug: airbyte
    status: profiled
    tags: &id002
    - Data Integration
    - ELT
    - ETL
    - Open Source
    url: /providers/airbyte/
  layer: common
  name: Airbyte
  provider: airbyte
  says: lists Airbyte as an integration
  source: https://www.close.com/integrations
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
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id003
      source: https://developer.calendly.com/calendly-mcp-server
      status: documented
    slug: calendly
    status: profiled
    tags: &id004
    - Appointments
    - Automation
    - Booking
    - Calendar
    url: /providers/calendly/
  layer: domain
  name: Calendly
  provider: calendly
  says: lists Calendly as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id005
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: ChatGPT
  provider: openai
  says: lists ChatGPT as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Claude
  provider: anthropic
  says: lists Claude as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.6
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id009
      source: https://clay.com/mcp
      status: verified
    slug: clay-com
    status: profiled
    tags: &id010
    - Data Enrichment
    - Go-To-Market
    - Prospecting
    - Sales
    url: /providers/clay-com/
  layer: domain
  name: Clay
  provider: clay-com
  says: lists Clay as an integration
  source: https://www.close.com/integrations
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
    agent_readiness: 70.1
    band: exemplar
    in_catalog: true
    kin_score: 85.9
    mcp: &id011
      source: https://github.com/customerio/claude-plugin
      status: verified
    slug: customer-io
    status: profiled
    tags: &id012
    - Behavioral Data
    - Broadcast
    - CDP
    - Campaigns
    url: /providers/customer-io/
  layer: domain
  name: Customer.io
  provider: customer-io
  says: lists Customer.io as an integration
  source: https://www.close.com/integrations
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
    mcp: &id013
      status: none
    slug: drip
    status: profiled
    tags: &id014
    - Customer Engagement
    - E-Commerce
    - Email Marketing
    - Marketing Automation
    url: /providers/drip/
  layer: domain
  name: Drip
  provider: drip
  says: lists Drip as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.5
    band: thin
    in_catalog: true
    kin_score: 32.1
    mcp: &id015
      status: unchecked
    slug: findymail
    status: profiled
    tags: &id016
    - B2B Data
    - Company
    - Email Finder
    - Lead Generation
    url: /providers/findymail/
  layer: domain
  name: Findymail
  provider: findymail
  says: lists Findymail as an integration
  source: https://www.close.com/integrations
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
    mcp: &id017
      source: https://docs.fireflies.ai/mcp-tools/overview
      status: verified
    slug: fireflies
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Meeting Assistant
    - Summary
    - Transcription
    url: /providers/fireflies/
  layer: domain
  name: Fireflies
  provider: fireflies
  says: lists Fireflies as an integration
  source: https://www.close.com/integrations
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
    mcp: &id019
      source: https://github.com/fivetran/fivetran-mcp
      status: verified
    slug: fivetran
    status: profiled
    tags: &id020
    - Connectors
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/fivetran/
  layer: common
  name: Fivetran
  provider: fivetran
  says: lists Fivetran as an integration
  source: https://www.close.com/integrations
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
    mcp: &id021
      source: https://www.geckoboard.com/product/metrics-mcp/
      status: verified
    slug: geckoboard
    status: profiled
    tags: &id022
    - Business Intelligence
    - Dashboards
    - Data Visualization
    - KPI Tracking
    url: /providers/geckoboard/
  layer: common
  name: Geckoboard
  provider: geckoboard
  says: lists Geckoboard as an integration
  source: https://www.close.com/integrations
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
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id023
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id024
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.close.com/integrations
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
    mcp: &id025
      status: none
    slug: gong
    status: profiled
    tags: &id026
    - Analytics
    - Conversations
    - Revenue Intelligence
    - Sales
    url: /providers/gong/
  layer: domain
  name: Gong
  provider: gong
  says: lists Gong as an integration
  source: https://www.close.com/integrations
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
  source: https://www.close.com/integrations
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
    mcp: &id029
      status: none
    slug: helpscout
    status: profiled
    tags: &id030
    - Customer Service
    - Email
    - Help Desk
    - Live Chat
    url: /providers/helpscout/
  layer: domain
  name: Help Scout
  provider: helpscout
  says: lists Help Scout as an integration
  source: https://www.close.com/integrations
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
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id031
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id032
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
  layer: common
  name: Hightouch
  provider: hightouch
  says: lists Hightouch as an integration
  source: https://www.close.com/integrations
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
    mcp: &id033
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id034
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.close.com/integrations
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
    mcp: &id035
      status: unchecked
    slug: jiminny
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - CRM Integration
    - Revenue
    - Sales Intelligence
    url: /providers/jiminny/
  layer: domain
  name: Jiminny
  provider: jiminny
  says: lists Jiminny as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: voice-telephony
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.4
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id037
      source: https://developer.justcall.io/docs/mcp
      status: verified
    slug: justcall
    status: profiled
    tags: &id038
    - Cloud Phone
    - Contact Center
    - SMS
    - Voice
    url: /providers/justcall/
  layer: domain
  name: JustCall
  provider: justcall
  says: lists JustCall as an integration
  source: https://www.close.com/integrations
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
    mcp: &id039
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id040
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.close.com/integrations
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
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id041
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id042
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://www.close.com/integrations
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
    mcp: &id043
      source: https://mcp.missiveapp.com/.well-known/oauth-protected-resource
      status: verified
    slug: missive
    status: profiled
    tags: &id044
    - Collaboration
    - Email
    - Messaging
    - Team Inbox
    url: /providers/missive/
  layer: domain
  name: Missive
  provider: missive
  says: lists Missive as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-931
    key: AE-931
    name: No-Code App Builders
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id045
      source: https://mcp.retool.com/mcp
      status: verified
    slug: retool
    status: profiled
    tags: &id046
    - Admin Panel
    - Dashboards
    - Internal Tools
    - Low-Code
    url: /providers/retool/
  layer: common
  name: Retool
  provider: retool
  says: lists Retool as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: voice-telephony
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id047
      status: none
    slug: ringover
    status: profiled
    tags: &id048
    - Cloud
    - Collaboration
    - Communications
    - VoIP
    url: /providers/ringover/
  layer: domain
  name: Ringover
  provider: ringover
  says: lists Ringover as an integration
  source: https://www.close.com/integrations
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
    mcp: &id049
      status: unchecked
    slug: salesmsg
    status: profiled
    tags: &id050
    - AI Agents
    - Business Calling
    - Business Texting
    - CRM Integration
    url: /providers/salesmsg/
  layer: domain
  name: Salesmsg
  provider: salesmsg
  says: lists Salesmsg as an integration
  source: https://www.close.com/integrations
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
    mcp: &id051
      status: none
    slug: segment
    status: profiled
    tags: &id052
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: lists Segment as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: qualified-electronic-signatures-trust-services
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id053
      source: https://www.signwell.com/resources/set-up-signwell-mcp/
      status: verified
    slug: signwell
    status: profiled
    tags: &id054
    - Documents
    - E-Signature
    - PDF
    - Signing
    url: /providers/signwell/
  layer: common
  name: SignWell
  provider: signwell
  says: lists SignWell as an integration
  source: https://www.close.com/integrations
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
    agent_readiness: 36.7
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id055
      source: https://mcp.skyvia.com/mcp
      status: verified
    slug: skyvia
    status: profiled
    tags: &id056
    - Data Integration
    - ELT
    - ETL
    - iPaaS
    url: /providers/skyvia/
  layer: common
  name: Skyvia
  provider: skyvia
  says: lists Skyvia as an integration
  source: https://www.close.com/integrations
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
    agent_band: human-only
    agent_readiness: 3.8
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id057
      status: none
    slug: stitch-data
    status: profiled
    tags: &id058
    - Cloud Data
    - Data Integration
    - Data Pipeline
    - ETL
    url: /providers/stitch-data/
  layer: common
  name: Stitch
  provider: stitch-data
  says: lists Stitch as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id059
      status: unknown
    slug: uplead
    status: profiled
    tags: &id060
    - B2B
    - Company Data
    - Contact Data
    - Lead Generation
    url: /providers/uplead/
  layer: domain
  name: UpLead
  provider: uplead
  says: lists UpLead as an integration
  source: https://www.close.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.7
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id061
      status: unchecked
    slug: voila-norbert
    status: profiled
    tags: &id062
    - Data Enrichment
    - Email Finder
    - Email Verification
    - Lead Generation
    url: /providers/voila-norbert/
  layer: domain
  name: Voila Norbert
  provider: voila-norbert
  says: lists Voila Norbert as an integration
  source: https://www.close.com/integrations
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
    mcp: &id063
      status: none
    slug: whatsapp
    status: profiled
    tags: &id064
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://www.close.com/integrations
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
    mcp: &id065
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id066
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.close.com/integrations
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
    mcp: &id067
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id068
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.close.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sales-engagement/close/
providers:
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 77.5
  mcp: *id001
  name: Airbyte
  slug: airbyte
  status: profiled
  tags: *id002
  url: /providers/airbyte/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id003
  name: Calendly
  slug: calendly
  status: profiled
  tags: *id004
  url: /providers/calendly/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id005
  name: ChatGPT
  slug: openai
  status: profiled
  tags: *id006
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Claude
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id009
  name: Clay
  slug: clay-com
  status: profiled
  tags: *id010
  url: /providers/clay-com/
- agent_band: agent-ready
  agent_readiness: 70.1
  band: exemplar
  in_catalog: true
  kin_score: 85.9
  mcp: *id011
  name: Customer.io
  slug: customer-io
  status: profiled
  tags: *id012
  url: /providers/customer-io/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id013
  name: Drip
  slug: drip
  status: profiled
  tags: *id014
  url: /providers/drip/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: thin
  in_catalog: true
  kin_score: 32.1
  mcp: *id015
  name: Findymail
  slug: findymail
  status: profiled
  tags: *id016
  url: /providers/findymail/
- agent_band: agent-ready
  agent_readiness: 59.4
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id017
  name: Fireflies
  slug: fireflies
  status: profiled
  tags: *id018
  url: /providers/fireflies/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id019
  name: Fivetran
  slug: fivetran
  status: profiled
  tags: *id020
  url: /providers/fivetran/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id021
  name: Geckoboard
  slug: geckoboard
  status: profiled
  tags: *id022
  url: /providers/geckoboard/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id023
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id024
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id025
  name: Gong
  slug: gong
  status: profiled
  tags: *id026
  url: /providers/gong/
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
- agent_band: agent-aware
  agent_readiness: 24.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id029
  name: Help Scout
  slug: helpscout
  status: profiled
  tags: *id030
  url: /providers/helpscout/
- agent_band: agent-ready
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id031
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id032
  url: /providers/hightouch/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id033
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id034
  url: /providers/hubspot/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 31.9
  mcp: *id035
  name: Jiminny
  slug: jiminny
  status: profiled
  tags: *id036
  url: /providers/jiminny/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id037
  name: JustCall
  slug: justcall
  status: profiled
  tags: *id038
  url: /providers/justcall/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id039
  name: Make
  slug: make
  status: profiled
  tags: *id040
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id041
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id042
  url: /providers/microsoft-365/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id043
  name: Missive
  slug: missive
  status: profiled
  tags: *id044
  url: /providers/missive/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id045
  name: Retool
  slug: retool
  status: profiled
  tags: *id046
  url: /providers/retool/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id047
  name: Ringover
  slug: ringover
  status: profiled
  tags: *id048
  url: /providers/ringover/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id049
  name: Salesmsg
  slug: salesmsg
  status: profiled
  tags: *id050
  url: /providers/salesmsg/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id051
  name: Segment
  slug: segment
  status: profiled
  tags: *id052
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id053
  name: SignWell
  slug: signwell
  status: profiled
  tags: *id054
  url: /providers/signwell/
- agent_band: agent-ready
  agent_readiness: 36.7
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id055
  name: Skyvia
  slug: skyvia
  status: profiled
  tags: *id056
  url: /providers/skyvia/
- agent_band: human-only
  agent_readiness: 3.8
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id057
  name: Stitch
  slug: stitch-data
  status: profiled
  tags: *id058
  url: /providers/stitch-data/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id059
  name: UpLead
  slug: uplead
  status: profiled
  tags: *id060
  url: /providers/uplead/
- agent_band: agent-aware
  agent_readiness: 12.7
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id061
  name: Voila Norbert
  slug: voila-norbert
  status: profiled
  tags: *id062
  url: /providers/voila-norbert/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id063
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id064
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id065
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id066
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id067
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id068
  url: /providers/zoom/
siblings:
- name: Aircall
  rows: 54
  url: /applications/sales-engagement/aircall/
- name: Apollo.io
  rows: 21
  url: /applications/sales-engagement/apollo-io/
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
title: 'Close: Sales Engagement & Dialers reference app'
---
