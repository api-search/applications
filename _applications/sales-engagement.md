---
access: understanding
agent_layer:
- app: Close
  finding: lists its own Close MCP server, and ChatGPT and Claude connectors, in its integrations directory
  source: https://www.close.com/integrations
  tier: declared
- app: Apollo.io
  finding: lists ChatGPT and Claude by Anthropic as integration partners
  source: https://www.apollo.io/product/integrations
  tier: declared
apps:
- anchor: close
  counts:
    declared: 34
    observed: 0
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
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.close.com/integrations
    tier: declared
  kind: commercial
  name: Close
  page: /applications/sales-engagement/close/
  slug: close
  url: https://www.close.com/
- anchor: lemlist
  counts:
    declared: 43
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.lemlist.com/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: voice-telephony
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: domain
    name: Aircall
    provider: aircall
    says: lists Aircall as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Albacross
    provider: albacross
    says: lists Albacross as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Apollo
    provider: apollo-io
    says: lists Apollo as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Attio
    provider: attio
    says: lists Attio as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Calendly
    provider: calendly
    says: lists Calendly as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Clay
    provider: clay-com
    says: lists Clay as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.30
      key: AE-150.10.30
      name: Email Deliverability & Verification
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Clearout
    provider: clearout
    says: lists Clearout as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: ClickFunnels
    provider: clickfunnels
    says: lists ClickFunnels as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Close
    provider: close
    says: lists Close as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: Eventbrite
    provider: eventbrite
    says: lists Eventbrite as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: Facebook Ads
    provider: facebook
    says: lists Facebook Ads as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Jotform
    provider: jotform
    says: lists Jotform as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Leadfeeder
    provider: leadfeeder
    says: lists Leadfeeder as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: LeadFuze
    provider: leadfuze
    says: lists LeadFuze as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: LinkedIn Ads
    provider: linkedin-ads
    says: lists LinkedIn Ads as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Lusha
    provider: lusha
    says: lists Lusha as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Monday
    provider: monday-com
    says: lists Monday as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: n8n
    provider: n8n
    says: lists n8n as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Notion
    provider: notion
    says: lists Notion as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Pabbly
    provider: pabbly
    says: lists Pabbly as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    credit: null
    layer: domain
    name: Phantombuster
    provider: phantombuster
    says: lists Phantombuster as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Pipedream
    provider: pipedream
    says: lists Pipedream as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pipedrive
    provider: pipedrive
    says: lists Pipedrive as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Relay.app
    provider: relay-app
    says: lists Relay.app as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: voice-telephony
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: domain
    name: Ringover
    provider: ringover
    says: lists Ringover as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Salesmsg
    provider: salesmsg
    says: lists Salesmsg as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.20
      key: AE-140.50.20
      name: Corporate & Digital Gifting
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    credit: null
    layer: domain
    name: Sendoso
    provider: sendoso
    says: lists Sendoso as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    credit: null
    layer: domain
    name: Sendspark
    provider: sendspark
    says: lists Sendspark as an integration
    source: https://www.lemlist.com/integrations
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
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Snitcher
    provider: snitcher
    says: lists Snitcher as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Uplead
    provider: uplead
    says: lists Uplead as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: domain
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zoho CRM
    provider: zoho-crm
    says: lists Zoho CRM as an integration
    source: https://www.lemlist.com/integrations
    tier: declared
  kind: commercial
  name: lemlist
  page: /applications/sales-engagement/lemlist/
  slug: lemlist
  url: https://www.lemlist.com/
- anchor: salesloft
  counts:
    declared: 4
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.salesloft.com/platform/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://www.salesloft.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: LinkedIn Sales Navigator
    provider: linkedin
    says: lists LinkedIn Sales Navigator as an integration
    source: https://www.salesloft.com/platform/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Outlook
    provider: microsoft-outlook
    says: lists Outlook as an integration
    source: https://www.salesloft.com/platform/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.salesloft.com/platform/integrations
    tier: declared
  kind: commercial
  name: Salesloft
  page: /applications/sales-engagement/salesloft/
  slug: salesloft
  url: https://www.salesloft.com/
- anchor: aircall
  counts:
    declared: 51
    observed: 3
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
    layer: domain
    name: Zoho Desk
    provider: zoho-desk
    says: lists Zoho Desk as an integration
    source: https://aircall.io/integrations/
    tier: declared
  kind: commercial
  name: Aircall
  page: /applications/sales-engagement/aircall/
  slug: aircall
  url: https://aircall.io/
- anchor: apolloio
  counts:
    declared: 21
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.apollo.io/product/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Adobe Marketo
    provider: marketo
    says: lists Adobe Marketo as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://www.apollo.io/product/integrations
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
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Census
    provider: getcensus
    says: lists Census as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: ChatGPT
    provider: openai
    says: lists ChatGPT as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Chili Piper
    provider: chili-piper
    says: lists Chili Piper as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Claude by Anthropic
    provider: anthropic
    says: lists Claude by Anthropic as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Clay
    provider: clay-com
    says: lists Clay as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: ClickUp
    provider: clickup
    says: lists ClickUp as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Coda
    provider: coda
    says: lists Coda as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: ContactOut
    provider: contactout
    says: lists ContactOut as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Dropcontact
    provider: dropcontact
    says: lists Dropcontact as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Findymail
    provider: findymail
    says: lists Findymail as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Docs
    provider: google-docs
    says: lists Google Docs as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Gumloop
    provider: gumloop
    says: lists Gumloop as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    credit: null
    layer: domain
    name: Hunter.io
    provider: hunter
    says: lists Hunter.io as an integration
    source: https://www.apollo.io/product/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://www.apollo.io/product/integrations
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
    source: https://www.apollo.io/product/integrations
    tier: declared
  kind: commercial
  name: Apollo.io
  page: /applications/sales-engagement/apollo-io/
  slug: apollo-io
  url: https://www.apollo.io/
- anchor: vicidial
  counts:
    declared: 1
    observed: 0
  evidence:
  - route: documentation
    url: https://www.vicidial.org/vicidial.php
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: voice-telephony
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    credit: null
    layer: domain
    name: Asterisk
    provider: asterisk
    says: lists Asterisk as an integration
    source: https://www.vicidial.org/vicidial.php
    tier: declared
  kind: self-hosted
  name: VICIdial
  page: /applications/sales-engagement/vicidial/
  slug: vicidial
  url: https://www.vicidial.org/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: sales-engagement
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Sales
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Sales
  store: hubspot-marketplace
  url: https://ecosystem.hubspot.com/marketplace/apps
- category: Sales
  store: aircall-marketplace
  url: https://aircall.io/integrations/
- category: Sales & CRM
  store: zapier
  url: https://zapier.com/apps
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
name: Sales Engagement & Dialers
needs:
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 5 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 4 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: integration category declared/observed in 4 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: nearest
  layer: common
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.10
    key: AE-230.30.10
    name: Data Enrichment
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: domain
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: voice-telephony
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: integration category declared/observed in 3 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: common
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: nearest
  layer: domain
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.30.20
    key: AE-230.30.20
    name: Lead Data
    url: /capabilities/company-contact-data/
    via_parent: Company & Contact Data
  fit: exact
  layer: domain
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: nearest
  layer: common
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: integration category declared/observed in 2 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: video-calling
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-931
    key: AE-931
    name: No-Code App Builders
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: common
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: qualified-electronic-signatures-trust-services
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  fit: nearest
  layer: common
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.60.10
    key: AE-150.60.10
    name: Async Video Messaging
    url: /capabilities/video-calling/
    via_parent: Video Calling
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-140.50.20
    key: AE-140.50.20
    name: Corporate & Digital Gifting
    url: /capabilities/gift-cards-gifting-cashback/
    via_parent: Gift Cards, Gifting & Cashback
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.10
    key: AE-230.40.10
    name: Web Scraping
    url: /capabilities/web-data/
    via_parent: Web Data
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.30
    key: AE-150.10.30
    name: Email Deliverability & Verification
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-954
    key: AE-954
    name: Sales Engagement & Sequencing
    url: /capabilities/sales-engagement-sequencing/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-410.70
    key: sales-performance-management
    name: Sales Performance Management
    url: /capabilities/sales-performance-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-4260
    key: customer-success-management
    name: Customer Success Management
    url: /capabilities/customer-success-management/
    via_parent: null
  fit: exact
  layer: domain
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: integration category declared/observed in 1 of 6 reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: integration category declared/observed in 1 of 6 reference apps
stack:
- capabilities:
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
      - Aircall
      - Apollo.io
      - Close
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://aircall.io/integrations/
      - https://www.apollo.io/product/integrations
      - https://www.close.com/integrations
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
      - Aircall
      - Apollo.io
      - Salesloft
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://aircall.io/integrations/
      - https://www.apollo.io/product/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Aircall
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        status: none
      name: Zoho CRM
      slug: zoho-crm
      sources:
      - https://aircall.io/integrations/
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - CRM
      - Lead Management
      - Marketing Automation
      - Sales
      tier: declared
      url: /providers/zoho-crm/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Aircall
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://aircall.io/integrations/
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: declared
      url: /providers/pipedrive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Aircall
      - lemlist
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        source: https://docs.attio.com/mcp/overview
        status: verified
      name: Attio
      slug: attio
      sources:
      - https://aircall.io/integrations/
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - CRM
      - Companies
      - Contacts
      - Sales
      tier: declared
      url: /providers/attio/
    - agent_band: agent-ready
      agent_readiness: 58.1
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 77.2
      mcp:
        source: https://developer.close.com/mcp
        status: verified
      name: Close
      slug: close
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - CRM
      - Calling
      - Inside Sales
      - Sales Engagement
      tier: declared
      url: /providers/close/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk Sell
      slug: zendesk-sell
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Leads
      - Sales
      - Sales Automation
      tier: declared
      url: /providers/zendesk-sell/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics
      slug: microsoft-dynamics-365
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
        status: verified
      name: HighLevel
      slug: highlevel
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Company
      - Marketing
      - Software-as-a-Service
      tier: declared
      url: /providers/highlevel/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Aircall
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        status: unchecked
      name: Kommo
      slug: kommo
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - CRM
      - Messaging
      - Sales
      tier: declared
      url: /providers/kommo/
    - agent_band: agent-aware
      agent_readiness: 5.3
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 36.9
      mcp:
        status: none
      name: Bullhorn
      slug: bullhorn
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Applicant Tracking
      - Company
      - Recruiting
      - Staffing
      tier: declared
      url: /providers/bullhorn/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 36.2
      mcp:
        status: none
      name: Freshsales
      slug: freshsales
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Contacts
      - Deals
      - Sales
      tier: declared
      url: /providers/freshsales/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        status: none
      name: Odoo
      slug: odoo
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Business Applications
      - CRM
      - ERP
      - Open Source
      tier: declared
      url: /providers/odoo/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.10
      key: AE-230.30.10
      name: Data Enrichment
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.6
      apps:
      - Apollo.io
      - Close
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 65.0
      mcp:
        source: https://clay.com/mcp
        status: verified
      name: Clay
      slug: clay-com
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Data Enrichment
      - Go-To-Market
      - Prospecting
      - Sales
      tier: declared
      url: /providers/clay-com/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Close
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: unknown
      name: UpLead
      slug: uplead
      sources:
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - B2B
      - Company Data
      - Contact Data
      - Lead Generation
      tier: declared
      url: /providers/uplead/
    - agent_band: agent-ready
      agent_readiness: 37.5
      apps:
      - Apollo.io
      - Close
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        status: unchecked
      name: Findymail
      slug: findymail
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.close.com/integrations
      status: profiled
      tags:
      - B2B Data
      - Company
      - Email Finder
      - Lead Generation
      tier: declared
      url: /providers/findymail/
    - agent_band: agent-ready
      agent_readiness: 60.8
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://github.com/lusha-oss/lusha-public-api-mcp
        status: verified
      name: Lusha
      slug: lusha
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - B2B
      - Contact Data
      - Data Enrichment
      - Sales Intelligence
      tier: declared
      url: /providers/lusha/
    - agent_band: agent-native
      agent_readiness: 59.2
      apps:
      - Apollo.io
      band: exemplar
      in_catalog: true
      kin_score: 73.8
      mcp:
        source: https://mcp.hunter.io/mcp
        status: verified
      name: Hunter.io
      slug: hunter
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Contact Discovery
      - Email
      - Email Verification
      - Lead Generation
      tier: declared
      url: /providers/hunter/
    - agent_band: agent-ready
      agent_readiness: 58.0
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 68.6
      mcp:
        source: https://docs.apollo.io/docs/apollo-mcp
        status: verified
      name: Apollo
      slug: apollo-io
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - B2B Data
      - Engagement
      - Prospecting
      - Sales Intelligence
      tier: declared
      url: /providers/apollo-io/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Apollo.io
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        status: unchecked
      name: Dropcontact
      slug: dropcontact
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - B2B
      - Data Enrichment
      - Email Finder
      - GDPR
      tier: declared
      url: /providers/dropcontact/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Apollo.io
      band: developing
      in_catalog: true
      kin_score: 53.2
      mcp:
        source: https://contactout.com/mcp-integration
        status: verified
      name: ContactOut
      slug: contactout
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Company
      - Contact Data
      - Data Enrichment
      - Email Finder
      tier: declared
      url: /providers/contactout/
    - agent_band: agent-native
      agent_readiness: 39.8
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: unchecked
      name: LeadFuze
      slug: leadfuze
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Data Enrichment
      - Lead Generation
      - Marketing
      - Sales
      tier: declared
      url: /providers/leadfuze/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Close
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: unchecked
      name: Voila Norbert
      slug: voila-norbert
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Data Enrichment
      - Email Finder
      - Email Verification
      - Lead Generation
      tier: declared
      url: /providers/voila-norbert/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.8
      apps:
      - Aircall
      - Close
      band: developing
      in_catalog: true
      kin_score: 51.5
      mcp:
        status: none
      name: Help Scout
      slug: helpscout
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Customer Service
      - Email
      - Help Desk
      - Live Chat
      tier: declared
      url: /providers/helpscout/
    - agent_band: agent-aware
      agent_readiness: 26.6
      apps:
      - Aircall
      - Close
      band: developing
      in_catalog: true
      kin_score: 47.6
      mcp:
        source: https://mcp.missiveapp.com/.well-known/oauth-protected-resource
        status: verified
      name: Missive
      slug: missive
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Email
      - Messaging
      - Team Inbox
      tier: declared
      url: /providers/missive/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Aircall
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        source: https://dev.frontapp.com/docs/mcp
        status: documented
      name: Front
      slug: front
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Email
      - Inbox
      tier: declared
      url: /providers/front/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Aircall
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Aircall
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/gorgias/mcp-cookbook
        status: verified
      name: Gorgias
      slug: gorgias
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Customer Service
      - E-Commerce
      - Help Desk
      - Shopify
      tier: declared
      url: /providers/gorgias/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 38.2
      mcp:
        source: https://mcp.trengo.com/.well-known/oauth-protected-resource/mcp
        status: verified
      name: Trengo
      slug: trengo
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Customer Engagement
      - Messaging
      - Omnichannel
      - Shared Inbox
      tier: declared
      url: /providers/trengo/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Re:amaze
      slug: reamaze
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Customer Service
      - Help Desk
      - Live Chat
      tier: declared
      url: /providers/reamaze/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Freshdesk
      slug: freshdesk
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Application
      - Automation
      - Customer Service
      - Help Desk
      tier: declared
      url: /providers/freshdesk/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 28.2
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Desk
      slug: zoho-desk
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Customer Service
      - Help Desk
      - Knowledge Base
      - Ticketing
      tier: declared
      url: /providers/zoho-desk/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 26.4
      mcp:
        status: none
      name: Kustomer
      slug: kustomer
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Customer Service
      - Help Desk
      - Messaging
      tier: declared
      url: /providers/kustomer/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - Aircall
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        source: https://docs.fireflies.ai/mcp-tools/overview
        status: verified
      name: Fireflies
      slug: fireflies
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Meeting Assistant
      - Summary
      - Transcription
      tier: declared
      url: /providers/fireflies/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Aircall
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        status: none
      name: Gong
      slug: gong
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Analytics
      - Conversations
      - Revenue Intelligence
      - Sales
      tier: declared
      url: /providers/gong/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - Aircall
      - Close
      band: thin
      in_catalog: true
      kin_score: 31.9
      mcp:
        status: unchecked
      name: Jiminny
      slug: jiminny
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - CRM Integration
      - Revenue
      - Sales Intelligence
      tier: declared
      url: /providers/jiminny/
    - agent_band: agent-ready
      agent_readiness: 43.7
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        source: https://www.avoma.com/agentic-platform/mcp
        status: documented
      name: Avoma
      slug: avoma
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Meeting Assistant
      - Sales Enablement
      tier: declared
      url: /providers/avoma/
    - agent_band: agent-aware
      agent_readiness: 27.2
      apps:
      - Aircall
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Chorus.ai
      slug: chorus-ai
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversations
      - Revenue Intelligence
      - Sales
      tier: declared
      url: /providers/chorus-ai/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 70.1
      apps:
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 85.9
      mcp:
        source: https://github.com/customerio/claude-plugin
        status: verified
      name: Customer.io
      slug: customer-io
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Behavioral Data
      - Broadcast
      - CDP
      - Campaigns
      tier: declared
      url: /providers/customer-io/
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 78.1
      mcp:
        source: https://developers.klaviyo.com/en/docs/klaviyo_mcp_server
        status: verified
      name: Klaviyo
      slug: klaviyo
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Customer Data
      - Email
      - Marketing
      - SMS
      tier: declared
      url: /providers/klaviyo/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Close
      band: strong
      in_catalog: true
      kin_score: 63.9
      mcp:
        status: none
      name: Drip
      slug: drip
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Customer Engagement
      - E-Commerce
      - Email Marketing
      - Marketing Automation
      tier: declared
      url: /providers/drip/
    - agent_band: agent-ready
      agent_readiness: 30.4
      apps:
      - Apollo.io
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: none
      name: Adobe Marketo
      slug: marketo
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Adobe
      - Automation
      - Marketing
      - Marketing Automation
      tier: declared
      url: /providers/marketo/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Close
      - Salesloft
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://www.close.com/integrations
      - https://www.salesloft.com/platform/integrations
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Salesloft
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook
      slug: microsoft-outlook
      sources:
      - https://www.salesloft.com/platform/integrations
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Close
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: declared
      url: /providers/google-calendar/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50
      key: voice-telephony
      name: Voice & Telephony
      url: /capabilities/voice-telephony/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Close
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 64.5
      mcp:
        status: none
      name: Ringover
      slug: ringover
      sources:
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Cloud
      - Collaboration
      - Communications
      - VoIP
      tier: declared
      url: /providers/ringover/
    - agent_band: agent-ready
      agent_readiness: 32.4
      apps:
      - Close
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://developer.justcall.io/docs/mcp
        status: verified
      name: JustCall
      slug: justcall
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Cloud Phone
      - Contact Center
      - SMS
      - Voice
      tier: declared
      url: /providers/justcall/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - lemlist
      band: thin
      in_catalog: true
      kin_score: 30.0
      mcp:
        status: none
      name: Aircall
      slug: aircall
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - CRM
      - Cloud Phone
      - Communications
      - Voice
      tier: declared
      url: /providers/aircall/
    - agent_band: null
      agent_readiness: null
      apps:
      - VICIdial
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Asterisk
      slug: asterisk
      sources:
      - https://www.vicidial.org/vicidial.php
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 84.3
      mcp:
        source: https://developer.bigcommerce.com/developer/docs/beta/store-management-mcp
        status: verified
      name: BigCommerce
      slug: bigcommerce
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Catalog
      - E-Commerce
      - Order
      - Retail
      tier: declared
      url: /providers/bigcommerce/
    - agent_band: agent-ready
      agent_readiness: 51.8
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 83.8
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
    - agent_band: agent-ready
      agent_readiness: 49.3
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        status: none
      name: ClickFunnels
      slug: clickfunnels
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - E-Commerce
      - Landing Pages
      - Marketing
      - Sales Funnels
      tier: declared
      url: /providers/clickfunnels/
    - agent_band: agent-ready
      agent_readiness: 62.5
      apps:
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://developers.webflow.com/mcp/reference/overview
        status: verified
      name: Webflow
      slug: webflow
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - No-Code
      - Web Development
      tier: declared
      url: /providers/webflow/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.30.20
      key: AE-230.30.20
      name: Lead Data
      url: /capabilities/company-contact-data/
      via_parent: Company & Contact Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Salesloft
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn Sales Navigator
      slug: linkedin
      sources:
      - https://www.salesloft.com/platform/integrations
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-ready
      agent_readiness: 48.5
      apps:
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 57.2
      mcp:
        status: unchecked
      name: Snitcher
      slug: snitcher
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - B2B SaaS
      - Company
      - Lead Generation
      - Visitor Intelligence
      tier: declared
      url: /providers/snitcher/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 47.1
      mcp:
        status: unchecked
      name: Leadfeeder
      slug: leadfeeder
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Analytics
      - B2B
      - Company
      - Lead Generation
      tier: declared
      url: /providers/leadfeeder/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 46.7
      mcp:
        source: https://mcp.albacross.com/.well-known/oauth-protected-resource/mcp
        status: verified
      name: Albacross
      slug: albacross
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - B2B Data
      - Company
      - Intent Data
      - Lead Generation
      tier: declared
      url: /providers/albacross/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Aircall
      - Apollo.io
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://www.chilipiper.com/products/mcp
        status: verified
      name: Chili Piper
      slug: chili-piper
      sources:
      - https://aircall.io/integrations/
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Lead Routing
      - Meetings
      - Sales
      - Scheduling
      tier: declared
      url: /providers/chili-piper/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Close
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 47.5
      mcp:
        source: https://developer.calendly.com/calendly-mcp-server
        status: documented
      name: Calendly
      slug: calendly
      sources:
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Appointments
      - Automation
      - Booking
      - Calendar
      tier: declared
      url: /providers/calendly/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.4
      apps:
      - Aircall
      - Close
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        status: unchecked
      name: Salesmsg
      slug: salesmsg
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - AI Agents
      - Business Calling
      - Business Texting
      - CRM Integration
      tier: declared
      url: /providers/salesmsg/
  - capability:
      attribution: API Evangelist extension
      id: AE-954
      key: AE-954
      name: Sales Engagement & Sequencing
      url: /capabilities/sales-engagement-sequencing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 78.7
      mcp:
        status: none
      name: Outreach
      slug: outreach
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Sales
      - Sales Engagement
      - Sequences
      tier: declared
      url: /providers/outreach/
    - agent_band: agent-ready
      agent_readiness: 63.9
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://api.lemlist.com/mcp
        status: verified
      name: lemlist
      slug: lemlist
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Cold Email
      - Email Outreach
      - Sales Automation
      - Sales Engagement
      tier: declared
      url: /providers/lemlist/
    - agent_band: agent-native
      agent_readiness: 44.4
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 62.7
      mcp:
        status: none
      name: Salesloft
      slug: salesloft
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - CRM
      - Cadences
      - Sales
      - Sales Engagement
      tier: declared
      url: /providers/salesloft/
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
      - Aircall
      - Close
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        status: none
      name: LinkedIn Ads
      slug: linkedin-ads
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Advertising
      - Lead Generation
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin-ads/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Facebook Ads
      slug: facebook
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: declared
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60.10
      key: AE-150.60.10
      name: Async Video Messaging
      url: /capabilities/video-calling/
      via_parent: Video Calling
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        source: https://apiv2.sendspark.com/api/mcp
        status: verified
      name: Sendspark
      slug: sendspark
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Company
      - Marketing
      - Sales
      - Video
      tier: declared
      url: /providers/sendspark/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.50.20
      key: AE-140.50.20
      name: Corporate & Digital Gifting
      url: /capabilities/gift-cards-gifting-cashback/
      via_parent: Gift Cards, Gifting & Cashback
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Sendoso
      slug: sendoso
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Corporate Gifting
      - Direct Mail
      - Marketing Automation
      - Sales Engagement
      tier: declared
      url: /providers/sendoso/
  - capability:
      attribution: Turbo EA
      id: BC-4260
      key: customer-success-management
      name: Customer Success Management
      url: /capabilities/customer-success-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 56.3
      mcp:
        source: https://help.planhat.com/en/articles/15644693-how-to-connect-chatgpt-to-planhat-using-oauth-and-planhat-s-mcp-server
        status: verified
      name: Planhat
      slug: planhat
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Company
      - Customer Platform
      - Customer Success
      - Software-as-a-Service
      tier: declared
      url: /providers/planhat/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 41.6
      mcp:
        status: none
      name: Eventbrite
      slug: eventbrite
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Event
      - Event Technology
      - Marketplace
      - Ticketing
      tier: declared
      url: /providers/eventbrite/
  - capability:
      attribution: Turbo EA
      id: BC-410.70
      key: sales-performance-management
      name: Sales Performance Management
      url: /capabilities/sales-performance-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 56.6
      mcp:
        status: none
      name: Mindtickle
      slug: mindtickle
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Coaching
      - Revenue Productivity
      - Sales Enablement
      - Sales Readiness
      tier: declared
      url: /providers/mindtickle/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: video-calling
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Close
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40.10
      key: AE-230.40.10
      name: Web Scraping
      url: /capabilities/web-data/
      via_parent: Web Data
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp:
        status: unchecked
      name: Phantombuster
      slug: phantombuster
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Automation
      - Company
      - Lead Generation
      - Sales
      tier: declared
      url: /providers/phantombuster/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Aircall
      - Close
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Aircall
      - Close
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Aircall
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 65.5
      mcp:
        source: https://pipedream.com/docs/connect/mcp
        status: verified
      name: Pipedream
      slug: pipedream
      sources:
      - https://aircall.io/integrations/
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Connect
      - Pipedream
      - Pro-Code-API-Composition
      - Workflows
      tier: declared
      url: /providers/pipedream/
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - Aircall
      band: exemplar
      in_catalog: true
      kin_score: 89.5
      mcp:
        source: https://docs.tray.ai/
        status: documented
      name: Tray.ai
      slug: tray-ai
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - AI Agents
      - Automation
      - Integration
      - iPaaS
      tier: declared
      url: /providers/tray-ai/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: declared
      url: /providers/n8n/
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - Apollo.io
      band: strong
      in_catalog: true
      kin_score: 65.6
      mcp:
        source: https://docs.gumloop.com/mcp-server/overview
        status: verified
      name: Gumloop
      slug: gumloop
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Automation
      - Company
      tier: declared
      url: /providers/gumloop/
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - lemlist
      band: developing
      in_catalog: true
      kin_score: 53.6
      mcp:
        status: none
      name: Pabbly
      slug: pabbly
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Automation
      - Billing
      - Email Marketing
      - Subscription Billing
      tier: declared
      url: /providers/pabbly/
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - lemlist
      band: thin
      in_catalog: true
      kin_score: 30.8
      mcp:
        status: unknown
      name: Relay.app
      slug: relay-app
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - Workflows
      tier: declared
      url: /providers/relay-app/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Aircall
      - Close
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Aircall
      - Close
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        source: https://github.com/fivetran/fivetran-mcp
        status: verified
      name: Fivetran
      slug: fivetran
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Connectors
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/fivetran/
    - agent_band: agent-ready
      agent_readiness: 44.2
      apps:
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 77.5
      mcp:
        status: none
      name: Airbyte
      slug: airbyte
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Data Integration
      - ELT
      - ETL
      - Open Source
      tier: declared
      url: /providers/airbyte/
    - agent_band: agent-ready
      agent_readiness: 62.8
      apps:
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://hightouch.com/docs/ai-integrations/mcp
        status: documented
      name: Hightouch
      slug: hightouch
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Audience Management
      - CDP
      - Data Activation
      - Reverse ETL
      tier: declared
      url: /providers/hightouch/
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - Apollo.io
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        status: none
      name: Census
      slug: getcensus
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Census
      - Data Activation
      - Reverse ETL
      - Sync
      tier: declared
      url: /providers/getcensus/
    - agent_band: agent-ready
      agent_readiness: 36.7
      apps:
      - Close
      band: strong
      in_catalog: true
      kin_score: 56.9
      mcp:
        source: https://mcp.skyvia.com/mcp
        status: verified
      name: Skyvia
      slug: skyvia
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Data Integration
      - ELT
      - ETL
      - iPaaS
      tier: declared
      url: /providers/skyvia/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - Close
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Stitch
      slug: stitch-data
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Cloud Data
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/stitch-data/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Apollo.io
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: declared
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Apollo.io
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Aircall
      - lemlist
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: Monday
      slug: monday-com
      sources:
      - https://aircall.io/integrations/
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Aircall
      - Apollo.io
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://aircall.io/integrations/
      - https://www.apollo.io/product/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Apollo.io
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Apollo.io
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Apollo.io
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Docs
      slug: google-docs
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Google Workspace
      - Productivity
      tier: declared
      url: /providers/google-docs/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - lemlist
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Apollo.io
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        status: none
      name: Coda
      slug: coda
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - Collaboration
      - Docs
      - No-Code
      - Productivity
      tier: declared
      url: /providers/coda/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - Aircall
      - Close
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        source: https://www.geckoboard.com/product/metrics-mcp/
        status: verified
      name: Geckoboard
      slug: geckoboard
      sources:
      - https://aircall.io/integrations/
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Business Intelligence
      - Dashboards
      - Data Visualization
      - KPI Tracking
      tier: declared
      url: /providers/geckoboard/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - lemlist
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://github.com/jotform/mcp-server
        status: verified
      name: Jotform
      slug: jotform
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Data Collection
      - Forms
      - No-Code
      - Surveys
      tier: declared
      url: /providers/jotform/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://aircall.io/integrations/
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
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
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Apollo.io
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://www.apollo.io/product/integrations
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: declared
      url: /providers/amplitude/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.30
      key: AE-150.10.30
      name: Email Deliverability & Verification
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - lemlist
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        status: unchecked
      name: Clearout
      slug: clearout
      sources:
      - https://www.lemlist.com/integrations
      status: profiled
      tags:
      - Company
      - Email Finder
      - Email Verification
      - Sales Prospecting
      tier: declared
      url: /providers/clearout/
  - capability:
      attribution: API Evangelist extension
      id: AE-931
      key: AE-931
      name: No-Code App Builders
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Close
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        source: https://mcp.retool.com/mcp
        status: verified
      name: Retool
      slug: retool
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Admin Panel
      - Dashboards
      - Internal Tools
      - Low-Code
      tier: declared
      url: /providers/retool/
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
      - Aircall
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Firebase Crashlytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.80
      key: qualified-electronic-signatures-trust-services
      name: Qualified Electronic Signatures & Trust Services
      url: /capabilities/qualified-electronic-signatures-trust-services/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Close
      band: thin
      in_catalog: true
      kin_score: 38.9
      mcp:
        source: https://www.signwell.com/resources/set-up-signwell-mcp/
        status: verified
      name: SignWell
      slug: signwell
      sources:
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Documents
      - E-Signature
      - PDF
      - Signing
      tier: declared
      url: /providers/signwell/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Aircall
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.aircall/latest/
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Apollo.io
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude
      slug: anthropic
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Apollo.io
      - Close
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT
      slug: openai
      sources:
      - https://www.apollo.io/product/integrations
      - https://www.close.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 99.1
  declared_only: 111
  distinct_providers: 113
  in_catalog: 112
  mcp:
    documented: 6
    none: 36
    unchecked: 12
    verified: 57
  mcp_verified: 57
  mean_kin_score: 58.4
  observed: 2
  queued: 1
  reference_apps: 6
title: 'Sales Engagement & Dialers: application blueprint'
---
