---
access: understanding
agent_layer:
- app: Vikunja
  finding: 'ships github.com/modelcontextprotocol/go-sdk: the server exposes its own MCP endpoint'
  source: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
  tier: observed
- app: TickTick
  finding: TickTick MCP and TickTick CLI help articles; built-in AI Assistant
  source: https://help.ticktick.com/articles/7055781878401335296
  tier: declared
- app: Todoist
  finding: Todoist ChatGPT app and Claude connector listed in its integrations directory
  source: https://www.todoist.com/integrations/category/all
  tier: declared
- app: Super Productivity
  finding: ai-productivity-prompts plugin
  source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
  tier: observed
apps:
- anchor: todoist
  counts:
    declared: 28
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
  - route: integrations page
    url: https://www.todoist.com/integrations/category/all
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Akiflow
    provider: akiflow
    says: lists Akiflow as an integration
    source: https://www.todoist.com/integrations/category/all
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
    name: Albato
    provider: albato
    says: lists Albato as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: Atlassian Rovo
    provider: atlassian
    says: lists Atlassian Rovo as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: ChatGPT app
    provider: openai
    says: lists ChatGPT app as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: Claude connector
    provider: anthropic
    says: lists Claude connector as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: BC-4330.10
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Everhour
    provider: everhour
    says: lists Everhour as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
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
    says: lists Evernote as an integration
    source: https://www.todoist.com/integrations/category/all
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
    name: Fantastical (Flexibits)
    provider: flexibits
    says: lists Fantastical (Flexibits) as an integration
    source: https://www.todoist.com/integrations/category/all
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
    name: Fireflies.ai
    provider: fireflies
    says: lists Fireflies.ai as an integration
    source: https://www.todoist.com/integrations/category/all
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
    source: https://www.todoist.com/integrations/category/all
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
    name: IFTTT
    provider: ifttt
    says: lists IFTTT as an integration
    source: https://www.todoist.com/integrations/category/all
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
    name: Integrately
    provider: integrately
    says: lists Integrately as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
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
    says: lists Jira as an integration
    source: https://www.todoist.com/integrations/category/all
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
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.todoist.com/integrations/category/all
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
    source: https://www.todoist.com/integrations/category/all
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
    name: Outlook / Outlook Calendar
    provider: microsoft-outlook
    says: lists Outlook / Outlook Calendar as an integration
    source: https://www.todoist.com/integrations/category/all
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
    source: https://www.todoist.com/integrations/category/all
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
    name: Raycast
    provider: raycast
    says: lists Raycast as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Reclaim.ai
    provider: reclaim-ai
    says: lists Reclaim.ai as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Sunsama
    provider: sunsama
    says: lists Sunsama as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: BC-4330.10
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    credit: null
    layer: domain
    name: Toggl Track
    provider: toggl
    says: lists Toggl Track as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
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
    says: lists Trello as an integration
    source: https://www.todoist.com/integrations/category/all
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
    source: https://www.todoist.com/integrations/category/all
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
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: common
    name: Zoho Cliq
    provider: zoho-cliq
    says: lists Zoho Cliq as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Zoho Mail
    provider: zoho-mail
    says: lists Zoho Mail as an integration
    source: https://www.todoist.com/integrations/category/all
    tier: declared
  kind: commercial
  name: Todoist
  page: /applications/task-todo/todoist/
  slug: todoist
  url: https://todoist.com/
- anchor: ticktick
  counts:
    declared: 7
    observed: 7
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
  - route: documentation
    url: https://help.ticktick.com/articles/7055781878401335296
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
    name: Bugsnag
    provider: bugsnag
    says: ships the Bugsnag SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
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
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
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
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: ships the Google Tag Manager SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
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
    name: Exchange Calendar
    provider: microsoft-exchange
    says: lists Exchange Calendar as an integration
    source: https://help.ticktick.com/articles/7055781878401335296
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
    source: https://help.ticktick.com/articles/7055781878401335296
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
    name: iCloud Calendar / Apple Health
    provider: apple
    says: lists iCloud Calendar / Apple Health as an integration
    source: https://help.ticktick.com/articles/7055781878401335296
    tier: declared
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
    says: lists Notion as an integration
    source: https://help.ticktick.com/articles/7055781878401335296
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
    name: Outlook Calendar
    provider: microsoft-outlook
    says: lists Outlook Calendar as an integration
    source: https://help.ticktick.com/articles/7055781878401335296
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
    name: Spark (Readdle)
    provider: readdle-spark
    says: lists Spark (Readdle) as an integration
    source: https://help.ticktick.com/articles/7055781878401335296
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: lists Telegram as an integration
    source: https://help.ticktick.com/articles/7055781878401335296
    tier: declared
  kind: commercial
  name: TickTick
  page: /applications/task-todo/ticktick/
  slug: ticktick
  url: https://ticktick.com/
- anchor: vikunja
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
  - route: source code
    url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background
  - route: source code
    url: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft To Do
    provider: microsoft-to-do
    says: ships the Microsoft To Do SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    name: Planka
    provider: planka
    says: ships the Planka SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: TickTick
    provider: ticktick
    says: ships the TickTick SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Todoist
    provider: todoist
    says: ships the Todoist SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
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
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    credit: null
    layer: common
    name: Unsplash
    provider: unsplash
    says: ships the Unsplash SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background
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
    name: WeKan
    provider: wekan
    says: ships the WeKan SDK or integration code
    source: https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
    tier: observed
  kind: self-hosted
  name: Vikunja
  page: /applications/task-todo/vikunja/
  slug: vikunja
  url: https://github.com/go-vikunja/vikunja
- anchor: tasksorg
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.tasks/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: EteSync
    provider: etesync
    says: ships the EteSync SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
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
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    credit: null
    layer: common
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Tasks
    provider: google-tasks
    says: ships the Google Tasks SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft To Do
    provider: microsoft-to-do
    says: ships the Microsoft To Do SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    credit: null
    layer: common
    name: OpenStreetMap
    provider: openstreetmap
    says: ships the OpenStreetMap SDK or integration code
    source: https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
    tier: observed
  kind: open-source-saas
  name: Tasks.org
  page: /applications/task-todo/tasks-org/
  slug: tasks-org
  url: https://github.com/tasks/tasks
- anchor: super-productivity
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: source code
    url: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
  - route: source code
    url: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
  - route: source code
    url: https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: ships the Azure DevOps SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
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
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
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
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
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
    name: Linear
    provider: linear-app
    says: ships the Linear SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    name: Nextcloud Deck
    provider: nextcloud
    says: ships the Nextcloud Deck SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    name: OneDrive
    provider: microsoft-onedrive
    says: ships the OneDrive SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
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
    name: OpenProject
    provider: openproject
    says: ships the OpenProject SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
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
    name: Redmine
    provider: redmine
    says: ships the Redmine SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: TickTick
    provider: ticktick
    says: ships the TickTick SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Todoist
    provider: todoist
    says: ships the Todoist SDK or integration code
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
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
    source: https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
    tier: observed
  kind: self-hosted
  name: Super Productivity
  page: /applications/task-todo/super-productivity/
  slug: super-productivity
  url: https://github.com/super-productivity/super-productivity
- anchor: donetick
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/donetick/donetick/main/go.mod
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Firebase Cloud Messaging
    provider: firebase
    says: ships the Firebase Cloud Messaging SDK or integration code
    source: https://raw.githubusercontent.com/donetick/donetick/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    credit: null
    layer: common
    name: Pushover
    provider: pushover
    says: ships the Pushover SDK or integration code
    source: https://raw.githubusercontent.com/donetick/donetick/main/go.mod
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
    source: https://raw.githubusercontent.com/donetick/donetick/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: common
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://raw.githubusercontent.com/donetick/donetick/main/go.mod
    tier: observed
  kind: self-hosted
  name: Donetick
  page: /applications/task-todo/donetick/
  slug: donetick
  url: https://github.com/donetick/donetick
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: task-todo
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Task Management & To-do Lists
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#task-management--to-do-lists
- category: Task Management
  store: zapier
  url: https://zapier.com/apps
name: Tasks & To-do Lists
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: due dates and time blocks round-trip to calendars; email-to-task
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: common
  why: tasks created from and posted to team chat
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: connector platforms that move tasks between apps
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: domain
  why: task lists, issue trackers and boards that a to-do app imports from or syncs with
- capability:
    attribution: API Evangelist extension
    id: AE-100.10
    key: AE-100.10
    name: Agent Tool Exposure
    url: /capabilities/agent-tool-exposure/
    via_parent: null
  fit: exact
  layer: agent
  why: the task app published into an AI assistant (ChatGPT, Claude, Rovo)
- capability:
    attribution: Turbo EA
    id: BC-830
    key: knowledge-management
    name: Knowledge Management
    url: /capabilities/knowledge-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: notes apps linked to tasks
- capability:
    attribution: API Evangelist extension
    id: AE-110.30.40
    key: AE-110.30.40
    name: Meeting Notes & Conversation Intelligence
    url: /capabilities/speech-voice/
    via_parent: Speech & Voice
  fit: exact
  layer: domain
  why: meeting action items become tasks
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: BC-4330.10
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  fit: exact
  layer: domain
  why: time tracking against tasks (nearest)
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: support tickets become tasks
- capability:
    attribution: API Evangelist extension
    id: AE-923
    key: AE-923
    name: Personal Task & To-Do Lists
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: auto-scheduling tasks into the day (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: task capture and reminders over Telegram
- capability:
    attribution: API Evangelist extension
    id: AE-170.30
    key: AE-170.30
    name: Photo & Image Libraries
    url: /capabilities/photo-image-libraries/
    via_parent: null
  fit: exact
  layer: common
  why: project backgrounds
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error and crash reporting
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: backup and device sync
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: premium unlock in the Android build
- capability:
    attribution: API Evangelist extension
    id: AE-120.20
    key: AE-120.20
    name: Maps & Tiles
    url: /capabilities/maps-tiles/
    via_parent: null
  fit: exact
  layer: common
  why: location-based reminders
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: reminders
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: hosted subscription billing
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: API Evangelist extension
    id: AE-170.50
    key: AE-170.50
    name: Social Networks & Community
    url: /capabilities/social-networks-community/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: SDK named in reference-app Exodus reports
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
      agent_readiness: 28.7
      apps:
      - Super Productivity
      - Todoist
      - Vikunja
      band: exemplar
      in_catalog: true
      kin_score: 75.6
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: observed
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 65.7
      apps:
      - Super Productivity
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 82.6
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: observed
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 55.6
      apps:
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 76.8
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: observed
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-ready
      agent_readiness: 57.0
      apps:
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
        status: verified
      name: ClickUp
      slug: clickup
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project Management
      - Work Management
      tier: observed
      url: /providers/clickup/
    - agent_band: agent-ready
      agent_readiness: 31.0
      apps:
      - Super Productivity
      band: exemplar
      in_catalog: true
      kin_score: 69.8
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: agent-ready
      agent_readiness: 32.0
      apps:
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 42.1
      mcp:
        source: https://www.openproject.org/docs/system-admin-guide/integrations/mcp-server/
        status: verified
      name: OpenProject
      slug: openproject
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/features/issue/providers
      status: profiled
      tags:
      - Agile
      - Gantt
      - Open Source
      - Project Management
      tier: observed
      url: /providers/openproject/
    - agent_band: agent-ready
      agent_readiness: 35.5
      apps:
      - Super Productivity
      band: thin
      in_catalog: true
      kin_score: 38.1
      mcp:
        source: https://linear.app/docs/mcp
        status: verified
      name: Linear
      slug: linear-app
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Issue Tracking
      - Productivity
      - Project Management
      - Software-as-a-Service
      tier: observed
      url: /providers/linear-app/
    - agent_band: human-only
      agent_readiness: 5.0
      apps:
      - Vikunja
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        status: none
      name: Planka
      slug: planka
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      status: profiled
      tags:
      - Agile
      - Kanban
      - Project Management
      - Self-Hosted
      tier: observed
      url: /providers/planka/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Super Productivity
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Nextcloud Deck
      slug: nextcloud
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Super Productivity
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: Redmine
      slug: redmine
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Issue Tracking
      - Open Source
      - Project Management
      - Ruby on Rails
      tier: observed
      url: /providers/redmine/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Vikunja
      band: emerging
      in_catalog: true
      kin_score: 18.6
      mcp:
        status: none
      name: WeKan
      slug: wekan
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/wekan/
  - capability:
      attribution: API Evangelist extension
      id: AE-923
      key: AE-923
      name: Personal Task & To-Do Lists
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 22.6
      apps:
      - Super Productivity
      - Vikunja
      band: strong
      in_catalog: true
      kin_score: 55.7
      mcp:
        source: https://developer.todoist.com/api/v1/#tag/MCP
        status: verified
      name: Todoist
      slug: todoist
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Productivity
      - Task
      - Task Management
      - To-Do
      tier: observed
      url: /providers/todoist/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Tasks.org
      - Vikunja
      band: developing
      in_catalog: true
      kin_score: 52.8
      mcp:
        status: none
      name: Microsoft To Do
      slug: microsoft-to-do
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Microsoft
      - Microsoft 365
      - Productivity
      - Task
      tier: observed
      url: /providers/microsoft-to-do/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Super Productivity
      - Vikunja
      band: emerging
      in_catalog: true
      kin_score: 17.6
      mcp:
        source: https://help.ticktick.com/articles/7438129581631995904
        status: verified
      name: TickTick
      slug: ticktick
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/migration
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      status: profiled
      tags:
      - Calendar
      - Company
      - Productivity
      - Task Management
      tier: observed
      url: /providers/ticktick/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - Tasks.org
      band: developing
      in_catalog: true
      kin_score: 47.0
      mcp:
        status: none
      name: Google Tasks
      slug: google-tasks
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Google
      - Productivity
      - Task
      - Task Management
      tier: observed
      url: /providers/google-tasks/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Tasks.org
      band: emerging
      in_catalog: true
      kin_score: 17.9
      mcp:
        status: none
      name: EteSync
      slug: etesync
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Company
      - Privacy
      - Security
      - Sync
      tier: observed
      url: /providers/etesync/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        status: none
      name: Reclaim.ai
      slug: reclaim-ai
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Artificial Intelligence
      - Calendar
      - Productivity
      - Scheduling
      tier: declared
      url: /providers/reclaim-ai/
    - agent_band: agent-aware
      agent_readiness: 21.6
      apps:
      - Todoist
      band: emerging
      in_catalog: true
      kin_score: 23.1
      mcp:
        source: https://help.sunsama.com/docs/integrations/mcp
        status: verified
      name: Sunsama
      slug: sunsama
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Calendar Integration
      - Company
      - Productivity
      - Task Management
      tier: declared
      url: /providers/sunsama/
    - agent_band: null
      agent_readiness: null
      apps:
      - Todoist
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Akiflow
      slug: akiflow
      sources:
      - https://www.todoist.com/integrations/category/all
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - Super Productivity
      - TickTick
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 48.8
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Calendar
      slug: google-calendar
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/packages/plugin-dev
      - https://help.ticktick.com/articles/7055781878401335296
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Availability
      - Calendar
      - Event
      - Google
      tier: observed
      url: /providers/google-calendar/
    - agent_band: agent-ready
      agent_readiness: 49.5
      apps:
      - TickTick
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 70.6
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook / Outlook Calendar
      slug: microsoft-outlook
      sources:
      - https://help.ticktick.com/articles/7055781878401335296
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 31.4
      apps:
      - TickTick
      band: strong
      in_catalog: true
      kin_score: 62.7
      mcp:
        status: none
      name: Exchange Calendar
      slug: microsoft-exchange
      sources:
      - https://help.ticktick.com/articles/7055781878401335296
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Contacts
      - Email
      tier: declared
      url: /providers/microsoft-exchange/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - TickTick
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: iCloud Calendar / Apple Health
      slug: apple
      sources:
      - https://help.ticktick.com/articles/7055781878401335296
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - TickTick
      band: emerging
      in_catalog: true
      kin_score: 21.2
      mcp:
        status: none
      name: Spark (Readdle)
      slug: readdle-spark
      sources:
      - https://help.ticktick.com/articles/7055781878401335296
      status: profiled
      tags:
      - Email
      - Productivity
      - iOS
      - macOS
      tier: declared
      url: /providers/readdle-spark/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Todoist
      band: emerging
      in_catalog: true
      kin_score: 12.0
      mcp:
        status: none
      name: Fantastical (Flexibits)
      slug: flexibits
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Calendar
      - Company
      - Productivity
      - macOS
      tier: declared
      url: /providers/flexibits/
  - capability:
      attribution: Turbo EA
      id: BC-830
      key: knowledge-management
      name: Knowledge Management
      url: /capabilities/knowledge-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.9
      apps:
      - TickTick
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://developers.notion.com/docs/mcp
        status: verified
      name: Notion
      slug: notion
      sources:
      - https://help.ticktick.com/articles/7055781878401335296
      status: profiled
      tags:
      - Collaboration
      - Database
      - Ideas
      - Notes
      tier: declared
      url: /providers/notion/
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 51.2
      mcp:
        source: https://dev.evernote.com/
        status: documented
      name: Evernote
      slug: evernote
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Company
      - Knowledge Management
      - Note Taking
      - Productivity
      tier: declared
      url: /providers/evernote/
  - capability:
      attribution: Turbo EA
      id: BC-4330.10
      key: BC-4330.10
      name: Timekeeping Management
      url: /capabilities/timekeeping-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Todoist
      band: thin
      in_catalog: true
      kin_score: 33.2
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=toggl
        status: verified
      name: Toggl Track
      slug: toggl
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Billing
      - Productivity
      - Project Management
      - Time Tracking
      tier: declared
      url: /providers/toggl/
    - agent_band: agent-aware
      agent_readiness: 23.1
      apps:
      - Todoist
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: none
      name: Everhour
      slug: everhour
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Productivity
      - Project Management
      - Time Tracking
      - Timesheets
      tier: declared
      url: /providers/everhour/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.30.40
      key: AE-110.30.40
      name: Meeting Notes & Conversation Intelligence
      url: /capabilities/speech-voice/
      via_parent: Speech & Voice
    providers:
    - agent_band: agent-ready
      agent_readiness: 60.4
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 72.7
      mcp:
        source: https://docs.fireflies.ai/mcp-tools/overview
        status: verified
      name: Fireflies.ai
      slug: fireflies
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Artificial Intelligence
      - Meeting Assistant
      - Summary
      - Transcription
      tier: declared
      url: /providers/fireflies/
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
      agent_readiness: 66.2
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 36.4
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 71.3
      mcp:
        source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
        status: verified
      name: n8n
      slug: n8n
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Agents
      - Artificial Intelligence
      - Integration
      - Workflows
      tier: declared
      url: /providers/n8n/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 67.3
      mcp:
        source: https://pipedream.com/docs/connect/mcp
        status: verified
      name: Pipedream
      slug: pipedream
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Connect
      - Pipedream
      - Pro-Code-API-Composition
      - Workflows
      tier: declared
      url: /providers/pipedream/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: Albato
      slug: albato
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - App Integration
      - Embedded iPaaS
      - No-Code Automation
      - Workflow Automation
      tier: declared
      url: /providers/albato/
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Integrately
      slug: integrately
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Automation
      - Business Process Automation
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/integrately/
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-aware
      agent_readiness: 13.6
      apps:
      - Todoist
      band: emerging
      in_catalog: true
      kin_score: 25.7
      mcp:
        status: none
      name: Raycast
      slug: raycast
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Extensions
      - Launcher
      - Productivity
      - SDK
      tier: declared
      url: /providers/raycast/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - Todoist
      band: emerging
      in_catalog: true
      kin_score: 25.0
      mcp:
        source: https://github.com/IFTTT/ifttt-plugins
        status: verified
      name: IFTTT
      slug: ifttt
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Automation
      - No-Code
      - Webhook
      - iPaaS
      tier: declared
      url: /providers/ifttt/
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
      - Todoist
      - Vikunja
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/go-vikunja/vikunja/main/go.mod
      - https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 53.1
      apps:
      - TickTick
      band: exemplar
      in_catalog: true
      kin_score: 78.5
      mcp:
        source: https://github.com/SmartBear/smartbear-mcp
        status: verified
      name: Bugsnag
      slug: bugsnag
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      status: profiled
      tags:
      - Application Performance Monitoring
      - Error Monitoring
      - Monitoring
      - Observability
      tier: observed
      url: /providers/bugsnag/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Tasks.org
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id001
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags: &id002
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - TickTick
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - TickTick
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - TickTick
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Tasks.org
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Super Productivity
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/super-productivity/super-productivity/tree/master/src/app/op-log/sync-providers/file-based
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 74.7
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: declared
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - Todoist
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 47.7
      mcp:
        source: https://www.zoho.com/mcp/
        status: verified
      name: Zoho Cliq
      slug: zoho-cliq
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Team Collaboration
      tier: declared
      url: /providers/zoho-cliq/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20
      key: AE-120.20
      name: Maps & Tiles
      url: /capabilities/maps-tiles/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Tasks.org
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Tasks.org
      band: developing
      in_catalog: true
      kin_score: 44.4
      mcp:
        status: none
      name: OpenStreetMap
      slug: openstreetmap
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Geocoding
      - Geospatial
      - Mapping
      - Open Data
      tier: observed
      url: /providers/openstreetmap/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Donetick
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id001
      name: Firebase Cloud Messaging
      slug: firebase
      sources:
      - https://raw.githubusercontent.com/donetick/donetick/main/go.mod
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-aware
      agent_readiness: 22.0
      apps:
      - Donetick
      band: thin
      in_catalog: true
      kin_score: 29.2
      mcp:
        status: none
      name: Pushover
      slug: pushover
      sources:
      - https://raw.githubusercontent.com/donetick/donetick/main/go.mod
      status: profiled
      tags:
      - Alerts
      - Messaging
      - Notification
      - Push Notifications
      tier: observed
      url: /providers/pushover/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - TickTick
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.50
      key: AE-170.50
      name: Social Networks & Community
      url: /capabilities/social-networks-community/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - TickTick
      - Todoist
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id003
      name: Facebook
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.todoist/latest/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Donetick
      - TickTick
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://help.ticktick.com/articles/7055781878401335296
      - https://raw.githubusercontent.com/donetick/donetick/main/go.mod
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Tasks.org
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/tasks/tasks/main/gradle/libs.versions.toml
      status: profiled
      tags:
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.6
      apps:
      - Todoist
      band: thin
      in_catalog: true
      kin_score: 36.4
      mcp:
        status: none
      name: Zoho Mail
      slug: zoho-mail
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Collaboration
      - Email
      - Mail
      - Messaging
      tier: declared
      url: /providers/zoho-mail/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Donetick
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://raw.githubusercontent.com/donetick/donetick/main/go.mod
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30
      key: AE-170.30
      name: Photo & Image Libraries
      url: /capabilities/photo-image-libraries/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.1
      apps:
      - Vikunja
      band: developing
      in_catalog: true
      kin_score: 40.2
      mcp:
        status: none
      name: Unsplash
      slug: unsplash
      sources:
      - https://github.com/go-vikunja/vikunja/tree/main/pkg/modules/background
      status: profiled
      tags:
      - Image
      - Photography
      - Photos
      - Stock Photos
      tier: observed
      url: /providers/unsplash/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - TickTick
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.ticktick.task/latest/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: observed
      url: /providers/google-tag-manager/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Claude connector
      slug: anthropic
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: ChatGPT app
      slug: openai
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: declared
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Todoist
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Atlassian Rovo
      slug: atlassian
      sources:
      - https://www.todoist.com/integrations/category/all
      status: profiled
      tags:
      - Code
      - Collaboration
      - Platform
      - Productivity
      tier: declared
      url: /providers/atlassian/
  layer: agent
summary:
  coverage_pct: 98.4
  declared_only: 29
  distinct_providers: 64
  in_catalog: 63
  mcp:
    documented: 1
    none: 27
    unchecked: 1
    verified: 35
  mcp_verified: 35
  mean_kin_score: 53.6
  observed: 35
  queued: 1
  reference_apps: 6
title: 'Tasks & To-do Lists: application blueprint'
---
