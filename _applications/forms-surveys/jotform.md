---
app: Jotform
app_slug: jotform
app_url: https://www.jotform.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - box
  - dropbox
  - google-drive
  - microsoft-onedrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - hubspot
  - keap
  - pipedrive
  - salesforce
  - zoho-crm
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - canva
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-400.60
  key: digital-marketing-management
  layer: domain
  name: Digital Marketing Management
  providers:
  - activecampaign
  - constant-contact
  - mailchimp
  url: /capabilities/digital-marketing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - microsoft-teams
  - slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - google-calendar
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - asana
  - monday.com
  - trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - airtable
  - google-sheets
  - microsoft-excel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - whatsapp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: domain
  name: Workflow Automation & iPaaS
  providers:
  - zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: common
  name: Hosted LLM Inference
  providers:
  - anthropic
  - openai
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Authorize.Net
  - paypal
  - square
  - stripe
  - worldpay
  url: /capabilities/payment-processing-management/
  via_parent: null
category:
  id: forms-surveys
  name: Forms & Surveys
  url: /applications/forms-surveys/
counts:
  declared: 32
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.jotform.com/integrations/
integrations:
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
  name: activecampaign
  provider: activecampaign
  says: lists activecampaign as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 50.3
    band: exemplar
    in_catalog: true
    kin_score: 69.2
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
  layer: domain
  name: airtable
  provider: airtable
  says: lists airtable as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
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
  layer: common
  name: anthropic
  provider: anthropic
  says: lists anthropic as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
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
  layer: domain
  name: asana
  provider: asana
  says: lists asana as an integration
  source: https://www.jotform.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id009
      source: https://github.com/AuthorizeNet/authorize-net-mcp
      status: verified
    slug: authorizenet
    status: profiled
    tags: &id010
    - Company
    - Credit Cards
    - Payment Gateway
    - Payments
    url: /providers/authorizenet/
  layer: common
  name: Authorize.Net
  provider: authorizenet
  says: lists Authorize.Net as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 57.4
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id011
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id012
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: box
  provider: box
  says: lists box as an integration
  source: https://www.jotform.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 71.4
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id013
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id014
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: canva
  provider: canva
  says: lists canva as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 32.1
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id015
      status: none
    slug: constant-contact
    status: profiled
    tags: &id016
    - Campaigns
    - Contacts
    - Email Marketing
    - Event
    url: /providers/constant-contact/
  layer: domain
  name: constant-contact
  provider: constant-contact
  says: lists constant-contact as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id017
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id018
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: dropbox
  provider: dropbox
  says: lists dropbox as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id019
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id020
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: domain
  name: google-calendar
  provider: google-calendar
  says: lists google-calendar as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 44.3
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id022
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: google-drive
  provider: google-drive
  says: lists google-drive as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 33.8
    band: strong
    in_catalog: true
    kin_score: 64.5
    mcp: &id023
      status: none
    slug: google-sheets
    status: profiled
    tags: &id024
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: google-sheets
  provider: google-sheets
  says: lists google-sheets as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id025
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id026
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: hubspot
  provider: hubspot
  says: lists hubspot as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id027
      status: none
    slug: keap
    status: profiled
    tags: &id028
    - CRM
    - Marketing Automation
    - Sales
    - Small Business
    url: /providers/keap/
  layer: domain
  name: keap
  provider: keap
  says: lists keap as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id029
      status: none
    slug: mailchimp
    status: profiled
    tags: &id030
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: mailchimp
  provider: mailchimp
  says: lists mailchimp as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 29.0
    band: developing
    in_catalog: true
    kin_score: 54.2
    mcp: &id031
      status: none
    slug: microsoft-excel
    status: profiled
    tags: &id032
    - Automation
    - Data Analysis
    - Microsoft
    - Microsoft 365
    url: /providers/microsoft-excel/
  layer: domain
  name: microsoft-excel
  provider: microsoft-excel
  says: lists microsoft-excel as an integration
  source: https://www.jotform.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id033
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id034
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: microsoft-onedrive
  provider: microsoft-onedrive
  says: lists microsoft-onedrive as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id035
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id036
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: microsoft-teams
  provider: microsoft-teams
  says: lists microsoft-teams as an integration
  source: https://www.jotform.com/integrations/
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
    kin_score: 33.6
    mcp: &id037
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id038
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: domain
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id039
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: common
  name: openai
  provider: openai
  says: lists openai as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 37.1
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id041
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id042
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: paypal
  provider: paypal
  says: lists paypal as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id043
      status: none
    slug: pipedrive
    status: profiled
    tags: &id044
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: domain
  name: pipedrive
  provider: pipedrive
  says: lists pipedrive as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id045
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id046
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: salesforce
  provider: salesforce
  says: lists salesforce as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id047
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id048
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: slack
  provider: slack
  says: lists slack as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id049
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id050
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: common
  name: square
  provider: square
  says: lists square as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 58.5
    band: exemplar
    in_catalog: true
    kin_score: 81.5
    mcp: &id051
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id052
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: stripe
  provider: stripe
  says: lists stripe as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id053
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id054
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: trello
  provider: trello
  says: lists trello as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id055
      status: none
    slug: whatsapp
    status: profiled
    tags: &id056
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: whatsapp
  provider: whatsapp
  says: lists whatsapp as an integration
  source: https://www.jotform.com/integrations/
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
    agent_readiness: 45.6
    band: developing
    in_catalog: true
    kin_score: 50.7
    mcp: &id057
      status: none
    slug: worldpay
    status: profiled
    tags: &id058
    - Payment Gateway
    - Payment Processing
    - Payments
    - Tokenization
    url: /providers/worldpay/
  layer: common
  name: worldpay
  provider: worldpay
  says: lists worldpay as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id059
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id060
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: domain
  name: zapier
  provider: zapier
  says: lists zapier as an integration
  source: https://www.jotform.com/integrations/
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
    mcp: &id061
      status: none
    slug: zoho-crm
    status: profiled
    tags: &id062
    - CRM
    - Lead Management
    - Marketing Automation
    - Sales
    url: /providers/zoho-crm/
  layer: domain
  name: zoho-crm
  provider: zoho-crm
  says: lists zoho-crm as an integration
  source: https://www.jotform.com/integrations/
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
  layer: domain
  name: zoom
  provider: zoom
  says: lists zoom as an integration
  source: https://www.jotform.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/forms-surveys/jotform/
providers:
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id001
  name: activecampaign
  slug: activecampaign
  status: profiled
  tags: *id002
  url: /providers/activecampaign/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id003
  name: airtable
  slug: airtable
  status: profiled
  tags: *id004
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id005
  name: anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id007
  name: asana
  slug: asana
  status: profiled
  tags: *id008
  url: /providers/asana/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id009
  name: Authorize.Net
  slug: authorizenet
  status: profiled
  tags: *id010
  url: /providers/authorizenet/
- agent_band: agent-ready
  agent_readiness: 57.4
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id011
  name: box
  slug: box
  status: profiled
  tags: *id012
  url: /providers/box/
- agent_band: agent-native
  agent_readiness: 71.4
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id013
  name: canva
  slug: canva
  status: profiled
  tags: *id014
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 32.1
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id015
  name: constant-contact
  slug: constant-contact
  status: profiled
  tags: *id016
  url: /providers/constant-contact/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id017
  name: dropbox
  slug: dropbox
  status: profiled
  tags: *id018
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id019
  name: google-calendar
  slug: google-calendar
  status: profiled
  tags: *id020
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 44.3
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id021
  name: google-drive
  slug: google-drive
  status: profiled
  tags: *id022
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 33.8
  band: strong
  in_catalog: true
  kin_score: 64.5
  mcp: *id023
  name: google-sheets
  slug: google-sheets
  status: profiled
  tags: *id024
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id025
  name: hubspot
  slug: hubspot
  status: profiled
  tags: *id026
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 45.4
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id027
  name: keap
  slug: keap
  status: profiled
  tags: *id028
  url: /providers/keap/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id029
  name: mailchimp
  slug: mailchimp
  status: profiled
  tags: *id030
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 29.0
  band: developing
  in_catalog: true
  kin_score: 54.2
  mcp: *id031
  name: microsoft-excel
  slug: microsoft-excel
  status: profiled
  tags: *id032
  url: /providers/microsoft-excel/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id033
  name: microsoft-onedrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id034
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id035
  name: microsoft-teams
  slug: microsoft-teams
  status: profiled
  tags: *id036
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id037
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id038
  url: /providers/monday-com/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id039
  name: openai
  slug: openai
  status: profiled
  tags: *id040
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id041
  name: paypal
  slug: paypal
  status: profiled
  tags: *id042
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 29.3
  band: strong
  in_catalog: true
  kin_score: 55.5
  mcp: *id043
  name: pipedrive
  slug: pipedrive
  status: profiled
  tags: *id044
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id045
  name: salesforce
  slug: salesforce
  status: profiled
  tags: *id046
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id047
  name: slack
  slug: slack
  status: profiled
  tags: *id048
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id049
  name: square
  slug: square
  status: profiled
  tags: *id050
  url: /providers/square/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id051
  name: stripe
  slug: stripe
  status: profiled
  tags: *id052
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id053
  name: trello
  slug: trello
  status: profiled
  tags: *id054
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id055
  name: whatsapp
  slug: whatsapp
  status: profiled
  tags: *id056
  url: /providers/whatsapp/
- agent_band: agent-native
  agent_readiness: 45.6
  band: developing
  in_catalog: true
  kin_score: 50.7
  mcp: *id057
  name: worldpay
  slug: worldpay
  status: profiled
  tags: *id058
  url: /providers/worldpay/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id059
  name: zapier
  slug: zapier
  status: profiled
  tags: *id060
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 44.2
  band: exemplar
  in_catalog: true
  kin_score: 86.0
  mcp: *id061
  name: zoho-crm
  slug: zoho-crm
  status: profiled
  tags: *id062
  url: /providers/zoho-crm/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id063
  name: zoom
  slug: zoom
  status: profiled
  tags: *id064
  url: /providers/zoom/
siblings:
- name: Formbricks
  rows: 16
  url: /applications/forms-surveys/formbricks/
- name: HeyForm
  rows: 6
  url: /applications/forms-surveys/heyform/
- name: LimeSurvey
  rows: 3
  url: /applications/forms-surveys/limesurvey/
- name: SurveyMonkey
  rows: 9
  url: /applications/forms-surveys/surveymonkey/
- name: Typebot
  rows: 23
  url: /applications/forms-surveys/typebot/
- name: Typeform
  rows: 18
  url: /applications/forms-surveys/typeform/
sitemap: true
title: 'Jotform: Forms & Surveys reference app'
---
