---
app: HoneyBook
app_slug: honeybook
app_url: https://www.honeybook.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Squarespace
  - Wix
  url: /capabilities/content-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.40
  key: AE-170.40
  layer: domain
  name: Creator Monetisation
  providers:
  - Kajabi
  url: /capabilities/creator-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: design-creative-editing
  layer: domain
  name: Design & Creative Editing
  providers:
  - Canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.20.30
  key: AE-120.20.30
  layer: domain
  name: Indoor & Venue Maps
  providers:
  - Prismm
  url: /capabilities/maps-tiles/
  via_parent: Maps & Tiles
- attribution: API Evangelist extension
  id: AE-170.20.10
  key: AE-170.20.10
  layer: domain
  name: Music Streaming & Catalog
  providers:
  - Vibo
  url: /capabilities/audio-music/
  via_parent: Audio & Music
- attribution: API Evangelist extension
  id: AE-170.30.20
  key: AE-170.30.20
  layer: domain
  name: Photo Sharing
  providers:
  - CloudSpot
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  - Google Docs
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - LeadConnector
  - Zoho
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: common
  name: Digital Marketing Management
  providers:
  - Facebook Conversions
  - Google Ads
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: common
  name: Email Marketing Sends
  providers:
  - ActiveCampaign
  - Flodesk
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - FreshBooks
  - QuickBooks
  - Wave
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Google Calendar
  - Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-921
  key: AE-921
  layer: common
  name: Online Forms & Survey Collection
  providers:
  - Google Forms
  - Typeform
  url: /capabilities/customer-feedback-management/
  via_parent: Customer Feedback Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Square
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: common
  name: Personal Task & To-Do Lists
  providers:
  - Todoist
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.50.10
  key: AE-150.50.10
  layer: common
  name: Programmable Voice
  providers:
  - Quo (OpenPhone)
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  - ClickUp
  - Monday
  - Motion
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2800.10
  key: scheduling-appointment-management
  layer: common
  name: Scheduling & Appointment Management
  providers:
  - Acuity
  - Calendly
  url: /capabilities/scheduling-appointment-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: common
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - ChatGPT
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: wedding-event-planning
  name: Wedding & Event Planning
  url: /applications/wedding-event-planning/
counts:
  declared: 40
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.honeybook.com/integrations
integrations:
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
  layer: common
  name: ActiveCampaign
  provider: activecampaign
  says: lists ActiveCampaign as an integration
  source: https://www.honeybook.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 24.0
    band: thin
    in_catalog: true
    kin_score: 29.6
    mcp: &id003
      status: none
    slug: acuity-scheduling
    status: profiled
    tags: &id004
    - Appointment Scheduling
    - Booking
    - Calendar
    - Scheduling
    url: /providers/acuity-scheduling/
  layer: common
  name: Acuity
  provider: acuity-scheduling
  says: lists Acuity as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: lists Anthropic as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id007
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id008
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id009
      source: https://developer.calendly.com/calendly-mcp-server
      status: documented
    slug: calendly
    status: profiled
    tags: &id010
    - Appointments
    - Automation
    - Booking
    - Calendar
    url: /providers/calendly/
  layer: common
  name: Calendly
  provider: calendly
  says: lists Calendly as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: design-creative-editing
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 70.0
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id011
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id012
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id013
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: ChatGPT
  provider: openai
  says: lists ChatGPT as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id015
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id016
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: common
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.20
    key: AE-170.30.20
    name: Photo Sharing
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id017
      status: unchecked
    slug: cloudspot
    status: profiled
    tags: &id018
    - Company
    - OnlineGallery
    - Photography
    - Software-as-a-Service
    url: /providers/cloudspot/
  layer: domain
  name: CloudSpot
  provider: cloudspot
  says: lists CloudSpot as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id019
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id020
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id021
      status: none
    slug: facebook
    status: profiled
    tags: &id022
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Conversions
  provider: facebook
  says: lists Facebook Conversions as an integration
  source: https://www.honeybook.com/integrations
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
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 19.8
    mcp: &id023
      status: unchecked
    slug: flodesk
    status: profiled
    tags: &id024
    - Automation
    - Email Marketing
    - Forms
    - Sales Funnels
    url: /providers/flodesk/
  layer: common
  name: Flodesk
  provider: flodesk
  says: lists Flodesk as an integration
  source: https://www.honeybook.com/integrations
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
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id025
      status: none
    slug: freshbooks
    status: profiled
    tags: &id026
    - Accounting
    - Expense Tracking
    - Invoicing
    - Time Tracking
    url: /providers/freshbooks/
  layer: common
  name: FreshBooks
  provider: freshbooks
  says: lists FreshBooks as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id027
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id028
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: gmail
  says: lists Gmail as an integration
  source: https://www.honeybook.com/integrations
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
    agent_readiness: 42.1
    band: exemplar
    in_catalog: true
    kin_score: 73.4
    mcp: &id029
      source: https://developers.google.com/google-ads/api/docs/developer-toolkit/mcp-server
      status: verified
    slug: google-ads
    status: profiled
    tags: &id030
    - Advertising
    - Campaign Management
    - Digital Advertising
    - Google
    url: /providers/google-ads/
  layer: common
  name: Google Ads
  provider: google-ads
  says: lists Google Ads as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id031
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id032
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.3
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id033
      source: https://docs.cloud.google.com/mcp/supported-products
      status: verified
    slug: google-docs
    status: profiled
    tags: &id034
    - Collaboration
    - Documents
    - Google Workspace
    - Productivity
    url: /providers/google-docs/
  layer: common
  name: Google Docs
  provider: google-docs
  says: lists Google Docs as an integration
  source: https://www.honeybook.com/integrations
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
    agent_readiness: 35.8
    band: developing
    in_catalog: true
    kin_score: 53.1
    mcp: &id035
      status: none
    slug: google-forms
    status: profiled
    tags: &id036
    - Data Collection
    - Forms
    - Google
    - Google Workspace
    url: /providers/google-forms/
  layer: common
  name: Google Forms
  provider: google-forms
  says: lists Google Forms as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id037
      status: none
    slug: google-sheets
    status: profiled
    tags: &id038
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: common
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.40
    key: AE-170.40
    name: Creator Monetisation
    url: /capabilities/creator-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 51.9
    band: developing
    in_catalog: true
    kin_score: 40.1
    mcp: &id039
      source: https://help.kajabi.com/en/collections/19761100-mcp
      status: documented
    slug: kajabi
    status: profiled
    tags: &id040
    - Creator Economy
    - E-Commerce
    - Membership
    - Online Courses
    url: /providers/kajabi/
  layer: domain
  name: Kajabi
  provider: kajabi
  says: lists Kajabi as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id041
      source: https://marketplace.gohighlevel.com/docs/other/mcp/index.html
      status: verified
    slug: highlevel
    status: profiled
    tags: &id042
    - CRM
    - Company
    - Marketing
    - Software-as-a-Service
    url: /providers/highlevel/
  layer: common
  name: LeadConnector
  provider: highlevel
  says: lists LeadConnector as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id043
      status: none
    slug: mailchimp
    status: profiled
    tags: &id044
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: common
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://www.honeybook.com/integrations
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
  source: https://www.honeybook.com/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id047
      status: unchecked
    slug: usemotion
    status: queued for profiling
    tags: &id048 []
    url: null
  layer: common
  name: Motion
  provider: usemotion
  says: lists Motion as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id049
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id050
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Outlook
  provider: microsoft-outlook
  says: lists Outlook as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.30
    key: AE-120.20.30
    name: Indoor & Venue Maps
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id051
      status: unchecked
    slug: prismm
    status: profiled
    tags: &id052
    - 3D Visualization
    - Event Planning
    - Spatial Design
    - Venue Marketing
    url: /providers/prismm/
  layer: domain
  name: Prismm
  provider: prismm
  says: lists Prismm as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id053
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id054
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.honeybook.com/integrations
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
    agent_readiness: 30.6
    band: strong
    in_catalog: true
    kin_score: 55.5
    mcp: &id055
      source: https://www.quo.com/docs/mdx/mcp
      status: verified
    slug: quo
    status: profiled
    tags: &id056
    - Communications
    - Company
    - Messaging
    - SMS
    url: /providers/quo/
  layer: common
  name: Quo (OpenPhone)
  provider: quo
  says: lists Quo (OpenPhone) as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id057
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id058
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.honeybook.com/integrations
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
  source: https://www.honeybook.com/integrations
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
  source: https://www.honeybook.com/integrations
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
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-923
    key: AE-923
    name: Personal Task & To-Do Lists
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.2
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id065
      source: https://developer.todoist.com/api/v1/#tag/MCP
      status: verified
    slug: todoist
    status: profiled
    tags: &id066
    - Productivity
    - Task
    - Task Management
    - To-Do
    url: /providers/todoist/
  layer: common
  name: Todoist
  provider: todoist
  says: lists Todoist as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id067
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id068
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: common
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.20.10
    key: AE-170.20.10
    name: Music Streaming & Catalog
    url: /capabilities/audio-music/
    via_parent: Audio & Music
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 16.6
    mcp: &id069
      status: unchecked
    slug: vibo
    status: profiled
    tags: &id070
    - DJ
    - Event Planning
    - Music
    - Software-as-a-Service
    url: /providers/vibo/
  layer: domain
  name: Vibo
  provider: vibo
  says: lists Vibo as an integration
  source: https://www.honeybook.com/integrations
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
    agent_readiness: 15.8
    band: thin
    in_catalog: true
    kin_score: 26.9
    mcp: &id071
      status: none
    slug: wave-financial
    status: profiled
    tags: &id072
    - Accounting
    - Finance
    - Invoicing
    - Small Business
    url: /providers/wave-financial/
  layer: common
  name: Wave
  provider: wave-financial
  says: lists Wave as an integration
  source: https://www.honeybook.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 47.2
    band: thin
    in_catalog: true
    kin_score: 35.5
    mcp: &id073
      source: https://dev.wix.com/docs/sdk/articles/use-the-wix-mcp/about-the-wix-mcp
      status: verified
    slug: wix
    status: profiled
    tags: &id074
    - CMS
    - E-Commerce
    - Headless
    - Website Builder
    url: /providers/wix/
  layer: domain
  name: Wix
  provider: wix
  says: lists Wix as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id075
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id076
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.honeybook.com/integrations
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
    agent_readiness: 32.4
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id077
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho
    status: profiled
    tags: &id078
    - Analytics
    - CRM
    - Collaboration
    - Customer Service
    url: /providers/zoho/
  layer: common
  name: Zoho
  provider: zoho
  says: lists Zoho as an integration
  source: https://www.honeybook.com/integrations
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
    mcp: &id079
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id080
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.honeybook.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/wedding-event-planning/honeybook/
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
- agent_band: agent-aware
  agent_readiness: 24.0
  band: thin
  in_catalog: true
  kin_score: 29.6
  mcp: *id003
  name: Acuity
  slug: acuity-scheduling
  status: profiled
  tags: *id004
  url: /providers/acuity-scheduling/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id007
  name: Asana
  slug: asana
  status: profiled
  tags: *id008
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 47.4
  band: developing
  in_catalog: true
  kin_score: 47.5
  mcp: *id009
  name: Calendly
  slug: calendly
  status: profiled
  tags: *id010
  url: /providers/calendly/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id011
  name: Canva
  slug: canva
  status: profiled
  tags: *id012
  url: /providers/canva/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id013
  name: ChatGPT
  slug: openai
  status: profiled
  tags: *id014
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id015
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id016
  url: /providers/clickup/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id017
  name: CloudSpot
  slug: cloudspot
  status: profiled
  tags: *id018
  url: /providers/cloudspot/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id019
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id020
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id021
  name: Facebook Conversions
  slug: facebook
  status: profiled
  tags: *id022
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 19.8
  mcp: *id023
  name: Flodesk
  slug: flodesk
  status: profiled
  tags: *id024
  url: /providers/flodesk/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id025
  name: FreshBooks
  slug: freshbooks
  status: profiled
  tags: *id026
  url: /providers/freshbooks/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id027
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id028
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 42.1
  band: exemplar
  in_catalog: true
  kin_score: 73.4
  mcp: *id029
  name: Google Ads
  slug: google-ads
  status: profiled
  tags: *id030
  url: /providers/google-ads/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id031
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id032
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 40.3
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id033
  name: Google Docs
  slug: google-docs
  status: profiled
  tags: *id034
  url: /providers/google-docs/
- agent_band: agent-ready
  agent_readiness: 35.8
  band: developing
  in_catalog: true
  kin_score: 53.1
  mcp: *id035
  name: Google Forms
  slug: google-forms
  status: profiled
  tags: *id036
  url: /providers/google-forms/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id037
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id038
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 51.9
  band: developing
  in_catalog: true
  kin_score: 40.1
  mcp: *id039
  name: Kajabi
  slug: kajabi
  status: profiled
  tags: *id040
  url: /providers/kajabi/
- agent_band: agent-ready
  agent_readiness: 37.5
  band: exemplar
  in_catalog: true
  kin_score: 66.9
  mcp: *id041
  name: LeadConnector
  slug: highlevel
  status: profiled
  tags: *id042
  url: /providers/highlevel/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id043
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id044
  url: /providers/mailchimp/
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
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id047
  name: Motion
  slug: usemotion
  status: queued for profiling
  tags: *id048
  url: null
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id049
  name: Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id050
  url: /providers/microsoft-outlook/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id051
  name: Prismm
  slug: prismm
  status: profiled
  tags: *id052
  url: /providers/prismm/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id053
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id054
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id055
  name: Quo (OpenPhone)
  slug: quo
  status: profiled
  tags: *id056
  url: /providers/quo/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id057
  name: Slack
  slug: slack
  status: profiled
  tags: *id058
  url: /providers/slack/
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
  agent_readiness: 22.2
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id065
  name: Todoist
  slug: todoist
  status: profiled
  tags: *id066
  url: /providers/todoist/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id067
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id068
  url: /providers/typeform/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 16.6
  mcp: *id069
  name: Vibo
  slug: vibo
  status: profiled
  tags: *id070
  url: /providers/vibo/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: thin
  in_catalog: true
  kin_score: 26.9
  mcp: *id071
  name: Wave
  slug: wave-financial
  status: profiled
  tags: *id072
  url: /providers/wave-financial/
- agent_band: agent-ready
  agent_readiness: 47.2
  band: thin
  in_catalog: true
  kin_score: 35.5
  mcp: *id073
  name: Wix
  slug: wix
  status: profiled
  tags: *id074
  url: /providers/wix/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id075
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id076
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id077
  name: Zoho
  slug: zoho
  status: profiled
  tags: *id078
  url: /providers/zoho/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id079
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id080
  url: /providers/zoom/
siblings:
- name: Aisle Planner
  rows: 6
  url: /applications/wedding-event-planning/aisle-planner/
- name: Joy
  rows: 12
  url: /applications/wedding-event-planning/joy/
- name: Planning Pod
  rows: 23
  url: /applications/wedding-event-planning/planning-pod/
- name: Rallly
  rows: 16
  url: /applications/wedding-event-planning/rallly/
- name: The Knot Wedding Planner
  rows: 0
  url: /applications/wedding-event-planning/the-knot-wedding-planner/
- name: WeddingShare
  rows: 2
  url: /applications/wedding-event-planning/weddingshare/
sitemap: true
title: 'HoneyBook: Wedding & Event Planning reference app'
---
