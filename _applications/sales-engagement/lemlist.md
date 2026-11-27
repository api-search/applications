---
app: lemlist
app_slug: lemlist
app_url: https://www.lemlist.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.60.10
  key: AE-150.60.10
  layer: domain
  name: Async Video Messaging
  providers:
  - Sendspark
  url: /capabilities/video-calling/
  via_parent: Video Calling
- attribution: API Evangelist extension
  id: AE-140.50.20
  key: AE-140.50.20
  layer: domain
  name: Corporate & Digital Gifting
  providers:
  - Sendoso
  url: /capabilities/gift-cards-gifting-cashback/
  via_parent: Gift Cards, Gifting & Cashback
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - Attio
  - Close
  - HubSpot
  - Pipedrive
  - Salesforce
  - Zoho CRM
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.10
  key: AE-230.30.10
  layer: domain
  name: Data Enrichment
  providers:
  - Apollo
  - Clay
  - LeadFuze
  - Lusha
  - Uplead
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - Facebook Ads
  - LinkedIn Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.50
  key: AE-210.50
  layer: domain
  name: Event Ticketing
  providers:
  - Eventbrite
  url: /capabilities/event-ticketing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.10.10
  key: AE-140.10.10
  layer: domain
  name: Hosted Storefronts
  providers:
  - ClickFunnels
  - Webflow
  url: /capabilities/storefront-platforms/
  via_parent: Storefront Platforms
- attribution: API Evangelist extension
  id: AE-230.30.20
  key: AE-230.30.20
  layer: domain
  name: Lead Data
  providers:
  - Albacross
  - Leadfeeder
  - Snitcher
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
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
  id: AE-150.50
  key: voice-telephony
  layer: domain
  name: Voice & Telephony
  providers:
  - Aircall
  - Ringover
  url: /capabilities/voice-telephony/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.40.10
  key: AE-230.40.10
  layer: domain
  name: Web Scraping
  providers:
  - Phantombuster
  url: /capabilities/web-data/
  via_parent: Web Data
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-150.10.30
  key: AE-150.10.30
  layer: common
  name: Email Deliverability & Verification
  providers:
  - Clearout
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Notion
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - Jotform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  - ClickUp
  - Monday
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Airtable
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - n8n
  - Pabbly
  - Pipedream
  - Relay.app
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: sales-engagement
  name: Sales Engagement & Dialers
  url: /applications/sales-engagement/
counts:
  declared: 43
  observed: 0
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 30.0
    mcp: &id001
      status: none
    slug: aircall
    status: profiled
    tags: &id002
    - CRM
    - Cloud Phone
    - Communications
    - Voice
    url: /providers/aircall/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id003
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id004
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id005
      source: https://mcp.albacross.com/.well-known/oauth-protected-resource/mcp
      status: verified
    slug: albacross
    status: profiled
    tags: &id006
    - B2B Data
    - Company
    - Intent Data
    - Lead Generation
    url: /providers/albacross/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.0
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id007
      source: https://docs.apollo.io/docs/apollo-mcp
      status: verified
    slug: apollo-io
    status: profiled
    tags: &id008
    - B2B Data
    - Engagement
    - Prospecting
    - Sales Intelligence
    url: /providers/apollo-io/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id009
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id010
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: emerging
    in_catalog: true
    kin_score: 20.0
    mcp: &id011
      source: https://docs.attio.com/mcp/overview
      status: verified
    slug: attio
    status: profiled
    tags: &id012
    - CRM
    - Companies
    - Contacts
    - Sales
    url: /providers/attio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.4
    band: developing
    in_catalog: true
    kin_score: 47.5
    mcp: &id013
      source: https://developer.calendly.com/calendly-mcp-server
      status: documented
    slug: calendly
    status: profiled
    tags: &id014
    - Appointments
    - Automation
    - Booking
    - Calendar
    url: /providers/calendly/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 59.6
    band: strong
    in_catalog: true
    kin_score: 65.0
    mcp: &id015
      source: https://clay.com/mcp
      status: verified
    slug: clay-com
    status: profiled
    tags: &id016
    - Data Enrichment
    - Go-To-Market
    - Prospecting
    - Sales
    url: /providers/clay-com/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id017
      status: unchecked
    slug: clearout
    status: profiled
    tags: &id018
    - Company
    - Email Finder
    - Email Verification
    - Sales Prospecting
    url: /providers/clearout/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id019
      status: none
    slug: clickfunnels
    status: profiled
    tags: &id020
    - E-Commerce
    - Landing Pages
    - Marketing
    - Sales Funnels
    url: /providers/clickfunnels/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id021
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id022
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.1
    band: exemplar
    in_catalog: true
    kin_score: 77.2
    mcp: &id023
      source: https://developer.close.com/mcp
      status: verified
    slug: close
    status: profiled
    tags: &id024
    - CRM
    - Calling
    - Inside Sales
    - Sales Engagement
    url: /providers/close/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id025
      status: none
    slug: eventbrite
    status: profiled
    tags: &id026
    - Event
    - Event Technology
    - Marketplace
    - Ticketing
    url: /providers/eventbrite/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id027
      status: none
    slug: facebook
    status: profiled
    tags: &id028
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id029
      status: none
    slug: google-sheets
    status: profiled
    tags: &id030
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id031
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id032
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id033
      source: https://github.com/jotform/mcp-server
      status: verified
    slug: jotform
    status: profiled
    tags: &id034
    - Data Collection
    - Forms
    - No-Code
    - Surveys
    url: /providers/jotform/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: developing
    in_catalog: true
    kin_score: 47.1
    mcp: &id035
      status: unchecked
    slug: leadfeeder
    status: profiled
    tags: &id036
    - Analytics
    - B2B
    - Company
    - Lead Generation
    url: /providers/leadfeeder/
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
  facts:
    agent_band: agent-native
    agent_readiness: 39.8
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id037
      status: unchecked
    slug: leadfuze
    status: profiled
    tags: &id038
    - Data Enrichment
    - Lead Generation
    - Marketing
    - Sales
    url: /providers/leadfuze/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 66.9
    mcp: &id039
      status: none
    slug: linkedin-ads
    status: profiled
    tags: &id040
    - Advertising
    - Lead Generation
    - LinkedIn
    - Marketing
    url: /providers/linkedin-ads/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 60.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id041
      source: https://github.com/lusha-oss/lusha-public-api-mcp
      status: verified
    slug: lusha
    status: profiled
    tags: &id042
    - B2B
    - Contact Data
    - Data Enrichment
    - Sales Intelligence
    url: /providers/lusha/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id045
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id046
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.7
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id047
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id048
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id049
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id050
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.9
    band: developing
    in_catalog: true
    kin_score: 53.6
    mcp: &id051
      status: none
    slug: pabbly
    status: profiled
    tags: &id052
    - Automation
    - Billing
    - Email Marketing
    - Subscription Billing
    url: /providers/pabbly/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id053
      status: unchecked
    slug: phantombuster
    status: profiled
    tags: &id054
    - Automation
    - Company
    - Lead Generation
    - Sales
    url: /providers/phantombuster/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id055
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id056
    - Connect
    - Pipedream
    - Pro-Code-API-Composition
    - Workflows
    url: /providers/pipedream/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id057
      status: none
    slug: pipedrive
    status: profiled
    tags: &id058
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: thin
    in_catalog: true
    kin_score: 30.8
    mcp: &id059
      status: unknown
    slug: relay-app
    status: profiled
    tags: &id060
    - Automation
    - Integration
    - No-Code
    - Workflows
    url: /providers/relay-app/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.3
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id061
      status: none
    slug: ringover
    status: profiled
    tags: &id062
    - Cloud
    - Collaboration
    - Communications
    - VoIP
    url: /providers/ringover/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id063
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id064
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.4
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id065
      status: unchecked
    slug: salesmsg
    status: profiled
    tags: &id066
    - AI Agents
    - Business Calling
    - Business Texting
    - CRM Integration
    url: /providers/salesmsg/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id067
      status: none
    slug: sendoso
    status: profiled
    tags: &id068
    - Corporate Gifting
    - Direct Mail
    - Marketing Automation
    - Sales Engagement
    url: /providers/sendoso/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id069
      source: https://apiv2.sendspark.com/api/mcp
      status: verified
    slug: sendspark
    status: profiled
    tags: &id070
    - Company
    - Marketing
    - Sales
    - Video
    url: /providers/sendspark/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id071
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id072
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.5
    band: strong
    in_catalog: true
    kin_score: 57.2
    mcp: &id073
      status: unchecked
    slug: snitcher
    status: profiled
    tags: &id074
    - B2B SaaS
    - Company
    - Lead Generation
    - Visitor Intelligence
    url: /providers/snitcher/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id075
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id076
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id077
      status: unknown
    slug: uplead
    status: profiled
    tags: &id078
    - B2B
    - Company Data
    - Contact Data
    - Lead Generation
    url: /providers/uplead/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id079
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id080
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id081
      status: none
    slug: whatsapp
    status: profiled
    tags: &id082
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id083
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id084
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.3
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id085
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id086
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: Zoho CRM
  provider: zoho-crm
  says: lists Zoho CRM as an integration
  source: https://www.lemlist.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/sales-engagement/lemlist/
providers:
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 30.0
  mcp: *id001
  name: Aircall
  slug: aircall
  status: profiled
  tags: *id002
  url: /providers/aircall/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id003
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id004
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id005
  name: Albacross
  slug: albacross
  status: profiled
  tags: *id006
  url: /providers/albacross/
- agent_band: agent-ready
  agent_readiness: 58.0
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id007
  name: Apollo
  slug: apollo-io
  status: profiled
  tags: *id008
  url: /providers/apollo-io/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id009
  name: Asana
  slug: asana
  status: profiled
  tags: *id010
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: emerging
  in_catalog: true
  kin_score: 20.0
  mcp: *id011
  name: Attio
  slug: attio
  status: profiled
  tags: *id012
  url: /providers/attio/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id013
  name: Calendly
  slug: calendly
  status: profiled
  tags: *id014
  url: /providers/calendly/
- agent_band: agent-ready
  agent_readiness: 59.6
  band: strong
  in_catalog: true
  kin_score: 65.0
  mcp: *id015
  name: Clay
  slug: clay-com
  status: profiled
  tags: *id016
  url: /providers/clay-com/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id017
  name: Clearout
  slug: clearout
  status: profiled
  tags: *id018
  url: /providers/clearout/
- agent_band: agent-ready
  agent_readiness: 49.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id019
  name: ClickFunnels
  slug: clickfunnels
  status: profiled
  tags: *id020
  url: /providers/clickfunnels/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id021
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id022
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 58.1
  band: exemplar
  in_catalog: true
  kin_score: 77.2
  mcp: *id023
  name: Close
  slug: close
  status: profiled
  tags: *id024
  url: /providers/close/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id025
  name: Eventbrite
  slug: eventbrite
  status: profiled
  tags: *id026
  url: /providers/eventbrite/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id027
  name: Facebook Ads
  slug: facebook
  status: profiled
  tags: *id028
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id029
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id030
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id031
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id032
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id033
  name: Jotform
  slug: jotform
  status: profiled
  tags: *id034
  url: /providers/jotform/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: developing
  in_catalog: true
  kin_score: 47.1
  mcp: *id035
  name: Leadfeeder
  slug: leadfeeder
  status: profiled
  tags: *id036
  url: /providers/leadfeeder/
- agent_band: agent-native
  agent_readiness: 39.8
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id037
  name: LeadFuze
  slug: leadfuze
  status: profiled
  tags: *id038
  url: /providers/leadfuze/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id039
  name: LinkedIn Ads
  slug: linkedin-ads
  status: profiled
  tags: *id040
  url: /providers/linkedin-ads/
- agent_band: agent-ready
  agent_readiness: 60.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id041
  name: Lusha
  slug: lusha
  status: profiled
  tags: *id042
  url: /providers/lusha/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id043
  name: Make
  slug: make
  status: profiled
  tags: *id044
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id045
  name: Monday
  slug: monday-com
  status: profiled
  tags: *id046
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id047
  name: n8n
  slug: n8n
  status: profiled
  tags: *id048
  url: /providers/n8n/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id049
  name: Notion
  slug: notion
  status: profiled
  tags: *id050
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 28.9
  band: developing
  in_catalog: true
  kin_score: 53.6
  mcp: *id051
  name: Pabbly
  slug: pabbly
  status: profiled
  tags: *id052
  url: /providers/pabbly/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id053
  name: Phantombuster
  slug: phantombuster
  status: profiled
  tags: *id054
  url: /providers/phantombuster/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id055
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id056
  url: /providers/pipedream/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id057
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id058
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: thin
  in_catalog: true
  kin_score: 30.8
  mcp: *id059
  name: Relay.app
  slug: relay-app
  status: profiled
  tags: *id060
  url: /providers/relay-app/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id061
  name: Ringover
  slug: ringover
  status: profiled
  tags: *id062
  url: /providers/ringover/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id063
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id064
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id065
  name: Salesmsg
  slug: salesmsg
  status: profiled
  tags: *id066
  url: /providers/salesmsg/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id067
  name: Sendoso
  slug: sendoso
  status: profiled
  tags: *id068
  url: /providers/sendoso/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id069
  name: Sendspark
  slug: sendspark
  status: profiled
  tags: *id070
  url: /providers/sendspark/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id071
  name: Slack
  slug: slack
  status: profiled
  tags: *id072
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 48.5
  band: strong
  in_catalog: true
  kin_score: 57.2
  mcp: *id073
  name: Snitcher
  slug: snitcher
  status: profiled
  tags: *id074
  url: /providers/snitcher/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id075
  name: Trello
  slug: trello
  status: profiled
  tags: *id076
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id077
  name: Uplead
  slug: uplead
  status: profiled
  tags: *id078
  url: /providers/uplead/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id079
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id080
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id081
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id082
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id083
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id084
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id085
  name: Zoho CRM
  slug: zoho-crm
  status: profiled
  tags: *id086
  url: /providers/zoho-crm/
siblings:
- name: Aircall
  rows: 54
  url: /applications/sales-engagement/aircall/
- name: Apollo.io
  rows: 21
  url: /applications/sales-engagement/apollo-io/
- name: Close
  rows: 34
  url: /applications/sales-engagement/close/
- name: Salesloft
  rows: 4
  url: /applications/sales-engagement/salesloft/
- name: VICIdial
  rows: 1
  url: /applications/sales-engagement/vicidial/
sitemap: true
title: 'lemlist: Sales Engagement & Dialers reference app'
---
