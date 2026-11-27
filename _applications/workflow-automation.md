---
access: understanding
agent_layer:
- app: Automatisch
  finding: ships an mcp app (MCP server trigger) and a self-hosted-llm app among its connectors
  source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
  tier: observed
- app: n8n
  finding: depends on @modelcontextprotocol/sdk, server and node packages plus @n8n/mcp-apps; MCP client and server nodes
  source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
  tier: observed
- app: Activepieces
  finding: depends on @modelcontextprotocol/sdk and @ai-sdk/mcp; pieces are exposed to agents as MCP tools
  source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  tier: observed
- app: Windmill
  finding: depends on rmcp and its own windmill-mcp crate
  source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
  tier: observed
- app: n8n
  finding: bring-your-own LLM across 11 model providers plus Ollama for local models
  source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  tier: observed
apps:
- anchor: automatisch
  counts:
    declared: 0
    observed: 76
  evidence:
  - route: source code
    url: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Airbrake
    provider: airbrake
    says: ships the Airbrake SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Airtable
    provider: airtable
    says: ships the Airtable SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.40
      key: AE-250.40
      name: Self-Hosted & Commercial Open Source
      url: /capabilities/self-hosted-commercial-open-source/
      via_parent: null
    credit: null
    layer: common
    name: Appwrite
    provider: appwrite
    says: ships the Appwrite SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Asana
    provider: asana
    says: ships the Asana SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Better Stack
    provider: betterstack
    says: ships the Better Stack SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40
      key: AE-230.40
      name: Web Data
      url: /capabilities/web-data/
      via_parent: null
    credit: null
    layer: domain
    name: Brave Search
    provider: brave-browser
    says: ships the Brave Search SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Carbone
    provider: carbone
    says: ships the Carbone SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40
      key: AE-230.40
      name: Web Data
      url: /capabilities/web-data/
      via_parent: null
    credit: null
    layer: domain
    name: changedetection.io
    provider: changedetection-io
    says: ships the changedetection.io SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: ClickUp
    provider: clickup
    says: ships the ClickUp SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: DeepL
    provider: deepl
    says: ships the DeepL SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Discord
    provider: discord
    says: ships the Discord SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Disqus
    provider: disqus
    says: ships the Disqus SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Eventbrite SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.10
      key: AE-190.10
      name: Budgeting & Money Management
      url: /capabilities/budgeting-money-management/
      via_parent: null
    credit: null
    layer: domain
    name: Firefly III
    provider: firefly-iii
    says: ships the Firefly III SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: domain
    name: Flickr
    provider: flickr
    says: ships the Flickr SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Flowers Software
    provider: flowers-software
    says: ships the Flowers Software SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Frappe
    provider: frappe
    says: ships the Frappe SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: FreeScout
    provider: freescout
    says: ships the FreeScout SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ghost
    provider: ghost-org
    says: ships the Ghost SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Gmail SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Docs
    provider: google-docs
    says: ships the Google Docs SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Google Forms
    provider: google-forms
    says: ships the Google Forms SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Sheets
    provider: google-sheets
    says: ships the Google Sheets SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Tasks
    provider: google-tasks
    says: ships the Google Tasks SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Helix (tryhelix.ai)
    provider: tryhelix
    says: ships the Helix (tryhelix.ai) SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the HubSpot SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Invoice Ninja
    provider: invoice-ninja
    says: ships the Invoice Ninja SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Jotform
    provider: jotform
    says: ships the Jotform SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: LibreTranslate
    provider: libre-translate
    says: ships the LibreTranslate SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
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
    name: Mailchimp
    provider: mailchimp
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
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
    name: MailerLite
    provider: mailerlite
    says: ships the MailerLite SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mattermost
    provider: mattermost
    says: ships the Mattermost SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Miro
    provider: miro
    says: ships the Miro SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: monday.com
    provider: monday-com
    says: ships the monday.com SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Notion
    provider: notion
    says: ships the Notion SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: ntfy
    provider: ntfy
    says: ships the ntfy SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Odoo SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter
    provider: openrouter
    says: ships the OpenRouter SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: PDFMonkey
    provider: pdf-monkey
    says: ships the PDFMonkey SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Perplexity
    provider: perplexity
    says: ships the Perplexity SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Pipedrive SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: Placetel
    provider: placetel
    says: ships the Placetel SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Reddit
    provider: reddit
    says: ships the Reddit SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: domain
    name: remove.bg
    provider: remove-bg
    says: ships the remove.bg SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Salesforce SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: SignalWire
    provider: signalwire
    says: ships the SignalWire SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: ships the Spotify SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    credit: null
    layer: domain
    name: Strava
    provider: strava
    says: ships the Strava SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: ships the Stripe SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: SurveyMonkey
    provider: surveymonkey
    says: ships the SurveyMonkey SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram Bot
    provider: telegram
    says: ships the Telegram Bot SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Todoist
    provider: todoist
    says: ships the Todoist SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Together AI
    provider: together-ai
    says: ships the Together AI SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Trello
    provider: trello
    says: ships the Trello SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Twitter / X
    provider: x
    says: ships the Twitter / X SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: domain
    name: Typeform
    provider: typeform
    says: ships the Typeform SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    credit: null
    layer: domain
    name: VirtualQ
    provider: virtualq
    says: ships the VirtualQ SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vtiger CRM
    provider: vtiger
    says: ships the Vtiger CRM SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: ships the WordPress SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: domain
    name: Xero
    provider: xero
    says: ships the Xero SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-190.10
      key: AE-190.10
      name: Budgeting & Money Management
      url: /capabilities/budgeting-money-management/
      via_parent: null
    credit: null
    layer: domain
    name: You Need A Budget
    provider: ynab
    says: ships the You Need A Budget SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
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
    says: ships the Zendesk SDK or integration code
    source: https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
    tier: observed
  kind: self-hosted
  name: Automatisch
  page: /applications/workflow-automation/automatisch/
  slug: automatisch
  url: https://github.com/automatisch/automatisch
- anchor: huginn
  counts:
    declared: 0
    observed: 25
  evidence:
  - route: dependency manifest
    url: https://github.com/huginn/huginn/blob/master/Gemfile
  - route: source code
    url: https://github.com/huginn/huginn/tree/master/app/models/agents
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    credit: null
    layer: domain
    name: AfterShip
    provider: aftership
    says: ships the AfterShip SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3 (aws-sdk-s3)
    provider: amazon-s3
    says: ships the Amazon S3 (aws-sdk-s3) SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Dropbox
    provider: dropbox
    says: ships the Dropbox SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    credit: null
    layer: domain
    name: Evernote
    provider: evernote
    says: ships the Evernote SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: domain
    name: Gmail (gmail_xoauth)
    provider: google-gmail
    says: ships the Gmail (gmail_xoauth) SDK or integration code
    source: https://github.com/huginn/huginn/blob/master/Gemfile
    tier: observed
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
    says: ships the Google Calendar SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Google Translate
    provider: google-translate
    says: ships the Google Translate SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: HipChat
    provider: hipchat
    says: ships the HipChat SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Jira
    provider: jira
    says: ships the Jira SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    credit: null
    layer: domain
    name: NextBus (public transport agent)
    provider: nextbus
    says: ships the NextBus (public transport agent) SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI (LLM, image, speech, video agents)
    provider: openai
    says: ships the OpenAI (LLM, image, speech, video agents) SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10.30
      key: AE-100.10.30
      name: Browser & Computer-Use Automation
      url: /capabilities/agent-tool-exposure/
      via_parent: Agent Tool Exposure
    credit: null
    layer: domain
    name: PhantomJS Cloud
    provider: phantomjscloud
    says: ships the PhantomJS Cloud SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    credit: null
    layer: domain
    name: Pirate Weather (pirate_weather_forecast_ruby)
    provider: pirate-weather
    says: ships the Pirate Weather (pirate_weather_forecast_ruby) SDK or integration code
    source: https://github.com/huginn/huginn/blob/master/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: Pushbullet
    provider: pushbullet
    says: ships the Pushbullet SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: domain
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Raindrop.io (bookmarks)
    provider: raindrop-io
    says: ships the Raindrop.io (bookmarks) SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    credit: null
    layer: domain
    name: StubHub
    provider: stubhub
    says: ships the StubHub SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Threads (Meta)
    provider: facebook
    says: ships the Threads (Meta) SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Tumblr
    provider: tumblr
    says: ships the Tumblr SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Twilio
    provider: twilio
    says: ships the Twilio SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Twitter / X
    provider: x
    says: ships the Twitter / X SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: null
    layer: domain
    name: Weibo
    provider: weibo
    says: ships the Weibo SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40
      key: AE-110.40
      name: Language & Document Understanding
      url: /capabilities/language-document-understanding/
      via_parent: null
    credit: null
    layer: domain
    name: Wit.ai
    provider: witai
    says: ships the Wit.ai SDK or integration code
    source: https://github.com/huginn/huginn/tree/master/app/models/agents
    tier: observed
  kind: self-hosted
  name: Huginn
  page: /applications/workflow-automation/huginn/
  slug: huginn
  url: https://github.com/huginn/huginn
- anchor: n8n
  counts:
    declared: 0
    observed: 39
  evidence:
  - route: dependency manifest
    url: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
  - route: dependency manifest
    url: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
  - route: dependency manifest
    url: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: 1Password Connect
    provider: 1password
    says: ships the 1Password Connect SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic (@langchain/anthropic)
    provider: anthropic
    says: ships the Anthropic (@langchain/anthropic) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS (@aws-sdk/credential-providers)
    provider: amazon-web-services
    says: ships the AWS (@aws-sdk/credential-providers) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS Secrets Manager
    provider: amazon-secrets-manager
    says: ships the AWS Secrets Manager SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Azure AI Search (@azure/search-documents)
    provider: azure-ai-search
    says: ships the Azure AI Search (@azure/search-documents) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: Azure Key Vault
    provider: microsoft-azure-key-vault
    says: ships the Azure Key Vault SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Chroma
    provider: chroma
    says: ships the Chroma SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Cohere
    provider: cohere
    says: ships the Cohere SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Confluent (@confluentinc/kafka-javascript, schema registry)
    provider: confluent
    says: ships the Confluent (@confluentinc/kafka-javascript, schema registry) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Discord (@chat-adapter/discord)
    provider: discord
    says: ships the Discord (@chat-adapter/discord) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Secret Manager
    provider: google-cloud-secret-manager
    says: ships the Google Cloud Secret Manager SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini (@google/genai, @langchain/google-genai)
    provider: google-gemini
    says: ships the Google Gemini (@google/genai, @langchain/google-genai) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Groq
    provider: groq
    says: ships the Groq SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Hugging Face (@huggingface/inference)
    provider: hugging-face
    says: ships the Hugging Face (@huggingface/inference) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    credit: null
    layer: agent
    name: LangSmith
    provider: langsmith
    says: ships the LangSmith SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Linear (@chat-adapter/linear)
    provider: linear-app
    says: ships the Linear (@chat-adapter/linear) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams (@chat-adapter/teams)
    provider: microsoft-teams
    says: ships the Microsoft Teams (@chat-adapter/teams) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Milvus (@zilliz/milvus2-sdk-node)
    provider: milvus
    says: ships the Milvus (@zilliz/milvus2-sdk-node) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Oracle Database (oracledb)
    provider: oracle
    says: ships the Oracle Database (oracledb) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Pinecone
    provider: pinecone
    says: ships the Pinecone SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog (posthog-node)
    provider: posthog
    says: ships the PostHog (posthog-node) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Qdrant
    provider: qdrant
    says: ships the Qdrant SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: RudderStack
    provider: rudderstack
    says: ships the RudderStack SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry (@sentry/node)
    provider: sentry-system
    says: ships the Sentry (@sentry/node) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: domain
    name: Slack (@chat-adapter/slack)
    provider: slack
    says: ships the Slack (@chat-adapter/slack) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake (snowflake-sdk)
    provider: snowflake
    says: ships the Snowflake (snowflake-sdk) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: SQL Server (mssql)
    provider: microsoft-sql-server
    says: ships the SQL Server (mssql) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Supabase (vector store)
    provider: supabase
    says: ships the Supabase (vector store) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram (@chat-adapter/telegram)
    provider: telegram
    says: ships the Telegram (@chat-adapter/telegram) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Vertex AI (@langchain/google-vertexai)
    provider: google-vertex-ai
    says: ships the Vertex AI (@langchain/google-vertexai) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Weaviate
    provider: weaviate
    says: ships the Weaviate SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: WhatsApp (@chat-adapter/whatsapp)
    provider: whatsapp
    says: ships the WhatsApp (@chat-adapter/whatsapp) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: agent
    name: Xata
    provider: xata
    says: ships the Xata SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-100.20.30
      key: AE-100.20.30
      name: Agent Runtime & Memory
      url: /capabilities/agent-to-agent-interoperability/
      via_parent: Agent-to-Agent Interoperability
    credit: null
    layer: agent
    name: Zep (@getzep/zep-cloud)
    provider: zep
    says: ships the Zep (@getzep/zep-cloud) SDK or integration code
    source: https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
    tier: observed
  kind: open-source-saas
  name: n8n
  page: /applications/workflow-automation/n8n/
  slug: n8n
  url: https://github.com/n8n-io/n8n
- anchor: activepieces
  counts:
    declared: 0
    observed: 15
  evidence:
  - route: dependency manifest
    url: https://github.com/activepieces/activepieces/blob/main/package.json
  - route: dependency manifest
    url: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: 1Password (@1password/sdk)
    provider: 1password
    says: ships the 1Password (@1password/sdk) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Amazon Bedrock (@ai-sdk/amazon-bedrock)
    provider: amazon-bedrock
    says: ships the Amazon Bedrock (@ai-sdk/amazon-bedrock) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3 (@aws-sdk/client-s3)
    provider: amazon-s3
    says: ships the Amazon S3 (@aws-sdk/client-s3) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Anthropic (@ai-sdk/anthropic)
    provider: anthropic
    says: ships the Anthropic (@ai-sdk/anthropic) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Autumn (autumn-js, billing)
    provider: autumn
    says: ships the Autumn (autumn-js, billing) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS Secrets Manager
    provider: amazon-secrets-manager
    says: ships the AWS Secrets Manager SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Azure OpenAI (@ai-sdk/azure)
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI (@ai-sdk/azure) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Cloudflare (cloudflare, ai-gateway-provider)
    provider: cloudflare
    says: ships the Cloudflare (cloudflare, ai-gateway-provider) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Google Gemini (@ai-sdk/google)
    provider: google-gemini
    says: ships the Google Gemini (@ai-sdk/google) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenAI (@ai-sdk/openai)
    provider: openai
    says: ships the OpenAI (@ai-sdk/openai) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: OpenRouter (@openrouter/sdk)
    provider: openrouter
    says: ships the OpenRouter (@openrouter/sdk) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: PostHog (posthog-node)
    provider: posthog
    says: ships the PostHog (posthog-node) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Replicate (@ai-sdk/replicate)
    provider: replicate
    says: ships the Replicate (@ai-sdk/replicate) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Sentry (@sentry/node)
    provider: sentry-system
    says: ships the Sentry (@sentry/node) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Vertex AI (@ai-sdk/google-vertex)
    provider: google-vertex-ai
    says: ships the Vertex AI (@ai-sdk/google-vertex) SDK or integration code
    source: https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
    tier: observed
  kind: open-source-saas
  name: Activepieces
  page: /applications/workflow-automation/activepieces/
  slug: activepieces
  url: https://github.com/activepieces/activepieces
- anchor: windmill
  counts:
    declared: 0
    observed: 12
  evidence:
  - route: dependency manifest
    url: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
  - route: dependency manifest
    url: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Amazon Bedrock (aws-sdk-bedrock)
    provider: amazon-bedrock
    says: ships the Amazon Bedrock (aws-sdk-bedrock) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3 (object_store aws)
    provider: amazon-s3
    says: ships the Amazon S3 (object_store aws) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Amazon SQS (sqs trigger)
    provider: amazon-sqs
    says: ships the Amazon SQS (sqs trigger) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS Secrets Manager
    provider: amazon-secrets-manager
    says: ships the AWS Secrets Manager SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Azure Blob Storage (object_store azure)
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage (object_store azure) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: BigQuery (bigquery feature)
    provider: google-bigquery
    says: ships the BigQuery (bigquery feature) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Google Cloud Pub/Sub (gcp trigger)
    provider: google-cloud-pubsub
    says: ships the Google Cloud Pub/Sub (gcp trigger) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Storage (object_store gcp)
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage (object_store gcp) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Oracle Database (oracle crate)
    provider: oracle
    says: ships the Oracle Database (oracle crate) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowflake (snowflake feature)
    provider: snowflake
    says: ships the Snowflake (snowflake feature) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: SQL Server (tiberius)
    provider: microsoft-sql-server
    says: ships the SQL Server (tiberius) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe (stripe feature)
    provider: stripe
    says: ships the Stripe (stripe feature) SDK or integration code
    source: https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
    tier: observed
  kind: open-source-saas
  name: Windmill
  page: /applications/workflow-automation/windmill/
  slug: windmill
  url: https://github.com/windmill-labs/windmill
- anchor: ifttt
  counts:
    declared: 0
    observed: 3
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Firebase (Crashlytics + Analytics)
    provider: firebase
    says: ships the Google Firebase (Crashlytics + Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
    tier: observed
  kind: commercial
  name: IFTTT
  page: /applications/workflow-automation/ifttt/
  slug: ifttt
  url: https://ifttt.com/
- anchor: microsoft-power-automate
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.flow/latest/
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
    name: Google Firebase Analytics
    provider: firebase
    says: ships the Google Firebase Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.flow/latest/
    tier: observed
  kind: commercial
  name: Microsoft Power Automate
  page: /applications/workflow-automation/microsoft-power-automate/
  slug: microsoft-power-automate
  url: https://www.microsoft.com/power-platform/products/power-automate
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: workflow-automation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Automation
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#automation
- category: Productivity
  store: slack-marketplace
  url: https://slack.com/apps
- category: Integration
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Automation
  store: zapier
  url: https://zapier.com/apps
name: Workflow Automation & iPaaS
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: nearest
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  fit: exact
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-210.50
    key: AE-210.50
    name: Event Ticketing
    url: /capabilities/event-ticketing/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: event-stream / queue triggers (Kafka via Confluent, SQS, Pub/Sub); no event-streaming node exists -- see Candidate extension nodes
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: operational database nodes (MongoDB, Oracle, SQL Server); no managed-database node exists -- see Candidate extension nodes
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-250.40
    key: AE-250.40
    name: Self-Hosted & Commercial Open Source
    url: /capabilities/self-hosted-commercial-open-source/
    via_parent: null
  fit: nearest
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.40
    key: AE-230.40
    name: Web Data
    url: /capabilities/web-data/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-2500.50
    key: electronic-documentation-management
    name: Electronic Documentation Management
    url: /capabilities/electronic-documentation-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-190.10
    key: AE-190.10
    name: Budgeting & Money Management
    url: /capabilities/budgeting-money-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.10
    key: AE-150.50.10
    name: Programmable Voice
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.50.10
    key: AE-110.50.10
    name: Image Recognition
    url: /capabilities/vision/
    via_parent: Vision
  fit: nearest
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.20
    key: AE-170.20
    name: Audio & Music
    url: /capabilities/audio-music/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-130.10.30
    key: AE-130.10.30
    name: Running & Cycling Tracking
    url: /capabilities/activity-fitness-tracking/
    via_parent: Activity & Fitness Tracking
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-170.10
    key: AE-170.10
    name: Video Platforms
    url: /capabilities/video-platforms/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-2510.20
    key: shipment-tracking-management
    name: Shipment Tracking Management
    url: /capabilities/shipment-tracking-management/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.40
    key: AE-110.40
    name: Language & Document Understanding
    url: /capabilities/language-document-understanding/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-100.10.30
    key: AE-100.10.30
    name: Browser & Computer-Use Automation
    url: /capabilities/agent-tool-exposure/
    via_parent: Agent Tool Exposure
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-210.30
    key: AE-210.30
    name: Ground Transport
    url: /capabilities/ground-transport/
    via_parent: null
  fit: nearest
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-230.10
    key: AE-230.10
    name: Weather & Environment
    url: /capabilities/weather-environment/
    via_parent: null
  fit: exact
  layer: domain
  why: connector/trigger category observed across reference apps
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  fit: nearest
  layer: common
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: agent
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-100.20.30
    key: AE-100.20.30
    name: Agent Runtime & Memory
    url: /capabilities/agent-to-agent-interoperability/
    via_parent: Agent-to-Agent Interoperability
  fit: exact
  layer: agent
  why: connector/trigger category observed across reference apps
- capability:
    attribution: API Evangelist extension
    id: AE-100.60.20
    key: AE-100.60.20
    name: Agent Observability
    url: /capabilities/agent-quality-operations/
    via_parent: Agent Quality & Operations
  fit: exact
  layer: agent
  why: connector/trigger category observed across reference apps
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Huginn
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: observed
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 72.6
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: observed
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: observed
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 54.9
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://developers.miro.com/docs/miro-mcp
        status: verified
      name: Miro
      slug: miro
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Diagramming
      - Productivity
      - Visual Collaboration
      - Whiteboard
      tier: observed
      url: /providers/miro/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        status: none
      name: Google Tasks
      slug: google-tasks
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Google
      - Productivity
      - Task
      - Task Management
      tier: observed
      url: /providers/google-tasks/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        source: https://developer.todoist.com/api/v1/#tag/MCP
        status: verified
      name: Todoist
      slug: todoist
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Productivity
      - Task
      - Task Management
      - To-Do
      tier: observed
      url: /providers/todoist/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - n8n
      band: developing
      in_catalog: true
      kin_score: 39.6
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear (@chat-adapter/linear)
      slug: linear-app
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: observed
      url: /providers/monday-com/
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
      - Automatisch
      - Huginn
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Automatisch
      - n8n
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - n8n
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams (@chat-adapter/teams)
      slug: microsoft-teams
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Huginn
      band: minimal
      in_catalog: true
      kin_score: 0.0
      mcp:
        status: none
      name: HipChat
      slug: hipchat
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Messaging
      - Team Communication
      tier: observed
      url: /providers/hipchat/
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
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: observed
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 55.3
      mcp:
        status: none
      name: Pipedrive
      slug: pipedrive
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - CRM
      - Pipeline Management
      - Sales
      - Software-as-a-Service
      tier: observed
      url: /providers/pipedrive/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Vtiger CRM
      slug: vtiger
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Artificial Intelligence
      - CRM
      - Company
      - Sales
      tier: observed
      url: /providers/vtiger/
    - agent_band: agent-aware
      agent_readiness: 22.2
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        source: https://github.com/frappe/mcp
        status: verified
      name: Frappe
      slug: frappe
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Accounting
      - ERP
      - Inventory
      - Open Source
      tier: observed
      url: /providers/frappe/
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 27.6
      mcp:
        status: none
      name: Odoo
      slug: odoo
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Business Applications
      - CRM
      - ERP
      - Open Source
      tier: observed
      url: /providers/odoo/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 13.4
      mcp:
        status: none
      name: Flowers Software
      slug: flowers-software
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Automation
      - Company
      - ERP
      - Finance
      tier: observed
      url: /providers/flowers-software/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Automatisch
      - Huginn
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter / X
      slug: x
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/reddit/devvit-mcp
        status: verified
      name: Reddit
      slug: reddit
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Advertising
      - Community
      - Content
      - Reddit
      tier: observed
      url: /providers/reddit/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Huginn
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        status: none
      name: Threads (Meta)
      slug: facebook
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 37.5
      mcp:
        status: none
      name: Disqus
      slug: disqus
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Comments
      - Community
      - Discussions
      - Publishing
      tier: observed
      url: /providers/disqus/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Huginn
      band: minimal
      in_catalog: true
      kin_score: 8.5
      mcp:
        status: none
      name: Tumblr
      slug: tumblr
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Public APIs
      - Social
      tier: observed
      url: /providers/tumblr/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - Huginn
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: none
      name: Weibo
      slug: weibo
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - China
      - Company
      - Microblogging
      - Social Media
      tier: observed
      url: /providers/weibo/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.8
      apps:
      - Windmill
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        source: https://github.com/oracle/mcp
        status: verified
      name: Oracle Database (oracledb)
      slug: oracle
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
      - https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
      status: profiled
      tags:
      - Cloud
      - Database
      - Enterprise
      - Oracle
      tier: observed
      url: /providers/oracle/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Windmill
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 67.0
      mcp:
        source: https://learn.microsoft.com/en-us/azure/data-api-builder/mcp/
        status: verified
      name: SQL Server (mssql)
      slug: microsoft-sql-server
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
      - https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
      status: profiled
      tags:
      - Cloud
      - Data Management
      - Database
      - Enterprise
      tier: observed
      url: /providers/microsoft-sql-server/
    - agent_band: agent-ready
      agent_readiness: 59.1
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: observed
      url: /providers/mongodb/
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
      - Automatisch
      - Huginn
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/blob/master/Gemfile
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: observed
      url: /providers/google-gmail/
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Automatisch
      - Huginn
      band: strong
      in_catalog: true
      kin_score: 64.6
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
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
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 70.2
      mcp:
        source: https://github.com/jotform/mcp-server
        status: verified
      name: Jotform
      slug: jotform
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Data Collection
      - Forms
      - No-Code
      - Surveys
      tier: observed
      url: /providers/jotform/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 53.1
      mcp:
        status: none
      name: Google Forms
      slug: google-forms
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Data Collection
      - Forms
      - Google
      - Google Workspace
      tier: observed
      url: /providers/google-forms/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: observed
      url: /providers/typeform/
    - agent_band: agent-ready
      agent_readiness: 46.9
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 34.9
      mcp:
        source: https://www.surveymonkey.com/apps/
        status: documented
      name: SurveyMonkey
      slug: surveymonkey
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Feedback
      - Market Research
      - NPS
      - Surveys
      tier: observed
      url: /providers/surveymonkey/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Automatisch
      - Huginn
      band: thin
      in_catalog: true
      kin_score: 28.1
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Huginn
      band: thin
      in_catalog: true
      kin_score: 30.2
      mcp:
        status: none
      name: Pushbullet
      slug: pushbullet
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Device Sync
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushbullet/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: ntfy
      slug: ntfy
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Notification
      - Open Source
      - Pub/Sub
      - Self-Hosted
      tier: observed
      url: /providers/ntfy/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Automatisch
      - Huginn
      - n8n
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram Bot
      slug: telegram
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp (@chat-adapter/whatsapp)
      slug: whatsapp
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: observed
      url: /providers/whatsapp/
  - capability:
      attribution: Turbo EA
      id: BC-610.50
      key: analytics-bi-management
      name: Analytics & BI Management
      url: /capabilities/analytics-bi-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - Windmill
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake (snowflake-sdk)
      slug: snowflake
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
      - https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: observed
      url: /providers/snowflake/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - Windmill
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: BigQuery (bigquery feature)
      slug: google-bigquery
      sources:
      - https://github.com/windmill-labs/windmill/blob/main/backend/windmill-worker/Cargo.toml
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: observed
      url: /providers/google-bigquery/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 87.2
      mcp:
        source: https://github.com/confluentinc/mcp-confluent
        status: verified
      name: Confluent (@confluentinc/kafka-javascript, schema registry)
      slug: confluent
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
      status: profiled
      tags:
      - Apache Kafka
      - Data Streaming
      - Event Streaming
      - Stream Processing
      tier: observed
      url: /providers/confluent/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - Windmill
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS (sqs trigger)
      slug: amazon-sqs
      sources:
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Windmill
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub (gcp trigger)
      slug: google-cloud-pubsub
      sources:
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: observed
      url: /providers/google-cloud-pubsub/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.3
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://docs.cloud.google.com/mcp/supported-products
        status: verified
      name: Google Docs
      slug: google-docs
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Collaboration
      - Documents
      - Google Workspace
      - Productivity
      tier: observed
      url: /providers/google-docs/
    - agent_band: agent-ready
      agent_readiness: 56.8
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: observed
      url: /providers/notion/
    - agent_band: agent-aware
      agent_readiness: 28.0
      apps:
      - Huginn
      band: developing
      in_catalog: true
      kin_score: 53.0
      mcp:
        source: https://dev.evernote.com/
        status: documented
      name: Evernote
      slug: evernote
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Company
      - Knowledge Management
      - Note Taking
      - Productivity
      tier: observed
      url: /providers/evernote/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Huginn
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Google Translate
      slug: google-translate
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: observed
      url: /providers/libre-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-native
      agent_readiness: 56.6
      apps:
      - Automatisch
      - Huginn
      band: exemplar
      in_catalog: true
      kin_score: 90.8
      mcp:
        source: https://www.twilio.com/docs/ai/mcp
        status: verified
      name: Twilio
      slug: twilio
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Authentication
      - Communications
      - Contact Center
      - Email
      tier: observed
      url: /providers/twilio/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 74.2
      mcp:
        status: none
      name: SignalWire
      slug: signalwire
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - CPaaS
      - Communications
      - Company
      - Voice
      tier: observed
      url: /providers/signalwire/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
  - capability:
      attribution: API Evangelist extension
      id: AE-190.10
      key: AE-190.10
      name: Budgeting & Money Management
      url: /capabilities/budgeting-money-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: minimal
      in_catalog: true
      kin_score: 8.7
      mcp:
        status: none
      name: Firefly III
      slug: firefly-iii
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Budgeting
      - Finance
      - Open Source
      - Personal Finance
      tier: observed
      url: /providers/firefly-iii/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - Automatisch
      band: minimal
      in_catalog: true
      kin_score: 8.1
      mcp:
        status: none
      name: You Need A Budget
      slug: ynab
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Finance
      - Public APIs
      tier: observed
      url: /providers/ynab/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 79.0
      mcp:
        status: none
      name: Ghost
      slug: ghost-org
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Membership
      - Newsletters
      - Publishing
      - Subscription
      tier: observed
      url: /providers/ghost-org/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: observed
      url: /providers/wordpress/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: none
      name: FreeScout
      slug: freescout
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Company
      - Help Desk
      - Open Source
      - PHP
      tier: observed
      url: /providers/freescout/
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://github.com/carboneio/carbone-mcp
        status: verified
      name: Carbone
      slug: carbone
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Document Generation
      - Open Source
      - PDF
      - Templates
      tier: observed
      url: /providers/carbone/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 32.1
      mcp:
        source: https://github.com/pdfmonkey/pdfmonkey-mcp
        status: verified
      name: PDFMonkey
      slug: pdf-monkey
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Document Generation
      - Handlebars
      - PDF
      - Templates
      tier: observed
      url: /providers/pdf-monkey/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 53.4
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.mailerlite.com/
        status: documented
      name: MailerLite
      slug: mailerlite
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Automation
      - Email Marketing
      - Newsletters
      - Subscribers
      tier: observed
      url: /providers/mailerlite/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.50
      key: AE-210.50
      name: Event Ticketing
      url: /capabilities/event-ticketing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.2
      apps:
      - Huginn
      band: developing
      in_catalog: true
      kin_score: 52.4
      mcp:
        status: none
      name: StubHub
      slug: stubhub
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Company
      - Event
      - Marketplace
      - Ticketing
      tier: observed
      url: /providers/stubhub/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 41.6
      mcp:
        status: none
      name: Eventbrite
      slug: eventbrite
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Event
      - Event Technology
      - Marketplace
      - Ticketing
      tier: observed
      url: /providers/eventbrite/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: observed
      url: /providers/xero/
    - agent_band: agent-aware
      agent_readiness: 18.0
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: none
      name: Invoice Ninja
      slug: invoice-ninja
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Accounting
      - Billing
      - Invoicing
      - Payments
      tier: observed
      url: /providers/invoice-ninja/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.50.10
      key: AE-150.50.10
      name: Programmable Voice
      url: /capabilities/voice-telephony/
      via_parent: Voice & Telephony
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: Placetel
      slug: placetel
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Call Center
      - Collaboration
      - Messaging
      - Video Meetings
      tier: observed
      url: /providers/placetel/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp:
        status: none
      name: VirtualQ
      slug: virtualq
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Appointment Management
      - Artificial Intelligence
      - Business
      - Customer Service
      tier: observed
      url: /providers/virtualq/
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
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: observed
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: observed
      url: /providers/google-sheets/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.40
      key: AE-230.40
      name: Web Data
      url: /capabilities/web-data/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.7
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 33.4
      mcp:
        source: https://github.com/brave/brave-search-mcp-server
        status: verified
      name: Brave Search
      slug: brave-browser
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Browser
      - Chromium
      - Privacy
      - Search
      tier: observed
      url: /providers/brave-browser/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 18.1
      mcp:
        status: none
      name: changedetection.io
      slug: changedetection-io
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Alerts
      - Company
      - Monitoring
      - Webhook
      tier: observed
      url: /providers/changedetection-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.20
      key: AE-170.20
      name: Audio & Music
      url: /capabilities/audio-music/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: observed
      url: /providers/spotify/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.1
      apps:
      - Huginn
      band: thin
      in_catalog: true
      kin_score: 29.1
      mcp:
        source: https://help.raindrop.io/integrations/mcp
        status: verified
      name: Raindrop.io (bookmarks)
      slug: raindrop-io
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Bookmark
      - Cloud
      - Collaboration
      - Productivity
      tier: observed
      url: /providers/raindrop-io/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10.30
      key: AE-100.10.30
      name: Browser & Computer-Use Automation
      url: /capabilities/agent-tool-exposure/
      via_parent: Agent Tool Exposure
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Huginn
      band: emerging
      in_catalog: true
      kin_score: 13.6
      mcp:
        status: unknown
      name: PhantomJS Cloud
      slug: phantomjscloud
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Automation
      - Browser API
      - Rendering
      - Web Scraping
      tier: observed
      url: /providers/phantomjscloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Automatisch
      band: minimal
      in_catalog: true
      kin_score: 4.8
      mcp:
        status: none
      name: remove.bg
      slug: remove-bg
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Photography
      - Public APIs
      tier: observed
      url: /providers/remove-bg/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40
      key: AE-110.40
      name: Language & Document Understanding
      url: /capabilities/language-document-understanding/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Huginn
      band: emerging
      in_catalog: true
      kin_score: 22.5
      mcp:
        status: none
      name: Wit.ai
      slug: witai
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Company
      - Natural Language Processing
      - Speech Recognition
      - Speech-to-Text
      tier: observed
      url: /providers/witai/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 49.1
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
  - capability:
      attribution: API Evangelist extension
      id: AE-210.30.40
      key: AE-210.30.40
      name: Public Transit Data
      url: /capabilities/ground-transport/
      via_parent: Ground Transport
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Huginn
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: NextBus (public transport agent)
      slug: nextbus
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-130.10.30
      key: AE-130.10.30
      name: Running & Cycling Tracking
      url: /capabilities/activity-fitness-tracking/
      via_parent: Activity & Fitness Tracking
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.3
      apps:
      - Automatisch
      band: developing
      in_catalog: true
      kin_score: 52.0
      mcp:
        status: none
      name: Strava
      slug: strava
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Cycling
      - Fitness
      - Fitness Tracking
      - Running
      tier: observed
      url: /providers/strava/
  - capability:
      attribution: Turbo EA
      id: BC-2510.20
      key: shipment-tracking-management
      name: Shipment Tracking Management
      url: /capabilities/shipment-tracking-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.9
      apps:
      - Huginn
      band: exemplar
      in_catalog: true
      kin_score: 83.3
      mcp:
        source: https://github.com/AfterShip/tracking-and-returns-mcp
        status: verified
      name: AfterShip
      slug: aftership
      sources:
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - E-Commerce
      - Post-Purchase
      - Shipping
      - Tracking
      tier: observed
      url: /providers/aftership/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10
      key: AE-170.10
      name: Video Platforms
      url: /capabilities/video-platforms/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
  - capability:
      attribution: API Evangelist extension
      id: AE-230.10
      key: AE-230.10
      name: Weather & Environment
      url: /capabilities/weather-environment/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Huginn
      band: minimal
      in_catalog: true
      kin_score: 2.4
      mcp:
        source: https://pirateweather.net/
        status: documented
      name: Pirate Weather (pirate_weather_forecast_ruby)
      slug: pirate-weather
      sources:
      - https://github.com/huginn/huginn/blob/master/Gemfile
      status: profiled
      tags:
      - Public APIs
      - Weather
      tier: observed
      url: /providers/pirate-weather/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4210.60
      key: configuration-secrets-management
      name: Configuration & Secrets Management
      url: /capabilities/configuration-secrets-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 39.2
      apps:
      - Activepieces
      - Windmill
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 77.5
      mcp:
        status: none
      name: AWS Secrets Manager
      slug: amazon-secrets-manager
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Configuration
      - Credentials
      - Rotation
      tier: observed
      url: /providers/amazon-secrets-manager/
    - agent_band: agent-ready
      agent_readiness: 33.6
      apps:
      - Activepieces
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 68.8
      mcp:
        source: https://1password.dev/environments/mcp-server
        status: verified
      name: 1Password Connect
      slug: 1password
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Password Manager
      - Passwords
      - Secrets
      - Security
      tier: observed
      url: /providers/1password/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        status: none
      name: Google Cloud Secret Manager
      slug: google-cloud-secret-manager
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Configuration
      - Credentials
      - Google Cloud
      - Key Management
      tier: observed
      url: /providers/google-cloud-secret-manager/
    - agent_band: agent-ready
      agent_readiness: 36.6
      apps:
      - n8n
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Key Vault
      slug: microsoft-azure-key-vault
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Certificates
      - Cloud Security
      - Cryptography
      - Key Management
      tier: observed
      url: /providers/microsoft-azure-key-vault/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Activepieces
      - n8n
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog (posthog-node)
      slug: posthog
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 79.1
      mcp:
        source: https://github.com/rudderlabs/rudderstack-mcp
        status: verified
      name: RudderStack
      slug: rudderstack
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - CDP
      - Customer Data Platform
      - Data Pipeline
      - Open Source
      tier: observed
      url: /providers/rudderstack/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Microsoft Power Automate
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google Firebase Analytics
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.microsoft.flow/latest/
      status: profiled
      tags: &id002
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - IFTTT
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - IFTTT
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Activepieces
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry (@sentry/node)
      slug: sentry-system
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 57.8
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://betterstack.com/docs/getting-started/integrations/mcp/
        status: documented
      name: Better Stack
      slug: betterstack
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Incidents
      - Logs
      - Observability
      - Uptime Monitoring
      tier: observed
      url: /providers/betterstack/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - IFTTT
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp: *id001
      name: Google Firebase (Crashlytics + Analytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ifttt.ifttt/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Automatisch
      band: emerging
      in_catalog: true
      kin_score: 25.8
      mcp:
        status: none
      name: Airbrake
      slug: airbrake
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Application Performance Monitoring
      - DevOps
      - Error Monitoring
      - Observability
      tier: observed
      url: /providers/airbrake/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Activepieces
      - Huginn
      - Windmill
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3 (aws-sdk-s3)
      slug: amazon-s3
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Windmill
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage (object_store gcp)
      slug: gcp-cloud-storage
      sources:
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Windmill
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage (object_store azure)
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Automatisch
      - Huginn
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Automatisch
      - Windmill
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-aware
      agent_readiness: 18.9
      apps:
      - Activepieces
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        source: https://docs.useautumn.com/documentation/mcp
        status: verified
      name: Autumn (autumn-js, billing)
      slug: autumn
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      status: profiled
      tags:
      - Billing
      - Company
      - Open Source
      - Stripe
      tier: observed
      url: /providers/autumn/
  - capability:
      attribution: Turbo EA
      id: BC-600.50
      key: it-infrastructure-management
      name: IT Infrastructure Management
      url: /capabilities/it-infrastructure-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS (@aws-sdk/credential-providers)
      slug: amazon-web-services
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/nodes-base/package.json
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: observed
      url: /providers/amazon-web-services/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.40
      key: AE-250.40
      name: Self-Hosted & Commercial Open Source
      url: /capabilities/self-hosted-commercial-open-source/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 57.8
      apps:
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://github.com/appwrite/mcp
        status: verified
      name: Appwrite
      slug: appwrite
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Application
      - Backend
      - Mobile
      - Open Source
      tier: observed
      url: /providers/appwrite/
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
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Activepieces
      - Automatisch
      - Huginn
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/huginn/huginn/tree/master/app/models/agents
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Activepieces
      - Automatisch
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - Activepieces
      - Windmill
      - n8n
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      - https://github.com/windmill-labs/windmill/blob/main/backend/Cargo.toml
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Activepieces
      - Automatisch
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Activepieces
      - n8n
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Vertex AI (@langchain/google-vertexai)
      slug: google-vertex-ai
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Activepieces
      - n8n
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini (@google/genai, @langchain/google-genai)
      slug: google-gemini
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Automatisch
      - n8n
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - n8n
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face (@huggingface/inference)
      slug: hugging-face
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
    - agent_band: agent-native
      agent_readiness: 66.6
      apps:
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 65.7
      mcp:
        source: https://github.com/perplexityai/modelcontextprotocol
        status: verified
      name: Perplexity
      slug: perplexity
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - LLM
      - Search
      tier: observed
      url: /providers/perplexity/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Activepieces
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        source: https://github.com/replicate/replicate-mcp-code-mode
        status: verified
      name: Replicate (@ai-sdk/replicate)
      slug: replicate
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Image Generation
      - Language Models
      - Machine Learning
      tier: observed
      url: /providers/replicate/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: observed
      url: /providers/cohere/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - Automatisch
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://docs.together.ai/docs/mcp
        status: verified
      name: Together AI
      slug: together-ai
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Inference
      - LLM
      tier: observed
      url: /providers/together-ai/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: observed
      url: /providers/groq/
    - agent_band: null
      agent_readiness: null
      apps:
      - Automatisch
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Helix (tryhelix.ai)
      slug: tryhelix
      sources:
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.20
      key: AE-110.60.20
      name: Vector Search
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - n8n
      band: strong
      in_catalog: true
      kin_score: 60.1
      mcp:
        source: https://github.com/pinecone-io/pinecone-mcp
        status: verified
      name: Pinecone
      slug: pinecone
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - RAG
      - Vector Search
      tier: observed
      url: /providers/pinecone/
    - agent_band: agent-ready
      agent_readiness: 39.7
      apps:
      - n8n
      band: strong
      in_catalog: true
      kin_score: 59.2
      mcp:
        source: https://github.com/chroma-core/chroma-mcp
        status: verified
      name: Chroma
      slug: chroma
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - AI-native
      - Apache 2.0
      - Artificial Intelligence
      - Cloud
      tier: observed
      url: /providers/chroma/
    - agent_band: agent-aware
      agent_readiness: 27.0
      apps:
      - n8n
      band: strong
      in_catalog: true
      kin_score: 58.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure AI Search (@azure/search-documents)
      slug: azure-ai-search
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud
      - Microsoft Azure
      - Search
      tier: observed
      url: /providers/azure-ai-search/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - n8n
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp:
        source: https://github.com/weaviate/mcp-server-weaviate
        status: verified
      name: Weaviate
      slug: weaviate
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Machine Learning
      - Semantic Search
      - Vector Search
      tier: observed
      url: /providers/weaviate/
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - n8n
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase (vector store)
      slug: supabase
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: observed
      url: /providers/supabase/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - n8n
      band: developing
      in_catalog: true
      kin_score: 40.0
      mcp:
        source: https://github.com/zilliztech/mcp-server-milvus
        status: verified
      name: Milvus (@zilliz/milvus2-sdk-node)
      slug: milvus
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Open Source
      - Vector Search
      tier: observed
      url: /providers/milvus/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        source: https://github.com/xataio/mcp
        status: verified
      name: Xata
      slug: xata
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Database
      - Developer Tools
      - PostgreSQL
      - Serverless
      tier: observed
      url: /providers/xata/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://github.com/qdrant/mcp-server-qdrant
        status: verified
      name: Qdrant
      slug: qdrant
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Database
      - Vector Search
      tier: observed
      url: /providers/qdrant/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Activepieces
      - Automatisch
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      - https://github.com/automatisch/automatisch/tree/main/packages/backend/src/apps
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Activepieces
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare (cloudflare, ai-gateway-provider)
      slug: cloudflare
      sources:
      - https://github.com/activepieces/activepieces/blob/main/packages/server/api/package.json
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: observed
      url: /providers/cloudflare/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.60.20
      key: AE-100.60.20
      name: Agent Observability
      url: /capabilities/agent-quality-operations/
      via_parent: Agent Quality & Operations
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 36.1
      mcp:
        source: https://github.com/langchain-ai/langsmith-mcp-server
        status: verified
      name: LangSmith
      slug: langsmith
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/cli/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Evaluation
      - LLM
      - Observability
      tier: observed
      url: /providers/langsmith/
  - capability:
      attribution: API Evangelist extension
      id: AE-100.20.30
      key: AE-100.20.30
      name: Agent Runtime & Memory
      url: /capabilities/agent-to-agent-interoperability/
      via_parent: Agent-to-Agent Interoperability
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.7
      apps:
      - n8n
      band: thin
      in_catalog: true
      kin_score: 38.3
      mcp:
        source: https://github.com/getzep/graphiti/tree/main/mcp_server
        status: verified
      name: Zep (@getzep/zep-cloud)
      slug: zep
      sources:
      - https://github.com/n8n-io/n8n/blob/master/packages/@n8n/nodes-langchain/package.json
      status: profiled
      tags:
      - AI Agents
      - Knowledge Graph
      - Memory
      - Temporal Graph
      tier: observed
      url: /providers/zep/
  layer: agent
summary:
  coverage_pct: 98.5
  declared_only: 0
  distinct_providers: 136
  in_catalog: 134
  mcp:
    documented: 5
    none: 47
    unchecked: 2
    verified: 81
  mcp_verified: 81
  mean_kin_score: 53.9
  observed: 136
  queued: 2
  reference_apps: 7
title: 'Workflow Automation & iPaaS: application blueprint'
---
