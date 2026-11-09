---
app: Todoist
app_slug: todoist
app_url: https://todoist.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830
  key: knowledge-management
  layer: domain
  name: Knowledge Management
  providers:
  - Evernote
  url: /capabilities/knowledge-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Fantastical (Flexibits)
  - Google Calendar
  - Outlook / Outlook Calendar
  - Zoho Mail
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.30.40
  key: AE-110.30.40
  layer: domain
  name: Meeting Notes & Conversation Intelligence
  providers:
  - Fireflies.ai
  url: /capabilities/speech-voice/
  via_parent: Speech & Voice
- attribution: API Evangelist extension
  id: AE-923
  key: AE-923
  layer: domain
  name: Personal Task & To-Do Lists
  providers:
  - Akiflow
  - Reclaim.ai
  - Sunsama
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Jira
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.10
  key: BC-4330.10
  layer: domain
  name: Timekeeping Management
  providers:
  - Everhour
  - Toggl Track
  url: /capabilities/timekeeping-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
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
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-170.50
  key: AE-170.50
  layer: common
  name: Social Networks & Community
  providers:
  - Facebook
  url: /capabilities/social-networks-community/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  - Zoho Cliq
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Albato
  - IFTTT
  - Integrately
  - Make
  - n8n
  - Pipedream
  - Raycast
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-100.10
  key: AE-100.10
  layer: agent
  name: Agent Tool Exposure
  providers:
  - Atlassian Rovo
  - ChatGPT app
  - Claude connector
  url: /capabilities/agent-tool-exposure/
  via_parent: null
category:
  id: task-todo
  name: Tasks & To-do Lists
  url: /applications/task-todo/
counts:
  declared: 28
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id016
      status: none
    slug: facebook
    status: profiled
    tags: &id017
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
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
  facts: *id001
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
  facts:
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id020
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id021
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id046
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id047
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id002
      status: unchecked
    slug: akiflow
    status: queued for profiling
    tags: &id003 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.5
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id004
      status: none
    slug: albato
    status: profiled
    tags: &id005
    - App Integration
    - Embedded iPaaS
    - No-Code Automation
    - Workflow Automation
    url: /providers/albato/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.6
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id006
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: atlassian
    status: profiled
    tags: &id007
    - Code
    - Collaboration
    - Platform
    - Productivity
    url: /providers/atlassian/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id008
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id009
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id010
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id011
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id012
      status: none
    slug: everhour
    status: profiled
    tags: &id013
    - Productivity
    - Project Management
    - Time Tracking
    - Timesheets
    url: /providers/everhour/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: developing
    in_catalog: true
    kin_score: 51.2
    mcp: &id014
      source: https://dev.evernote.com/
      status: documented
    slug: evernote
    status: profiled
    tags: &id015
    - Company
    - Knowledge Management
    - Note Taking
    - Productivity
    url: /providers/evernote/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.0
    mcp: &id018
      status: none
    slug: flexibits
    status: profiled
    tags: &id019
    - Calendar
    - Company
    - Productivity
    - macOS
    url: /providers/flexibits/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 60.4
    band: exemplar
    in_catalog: true
    kin_score: 72.7
    mcp: &id022
      source: https://docs.fireflies.ai/mcp-tools/overview
      status: verified
    slug: fireflies
    status: profiled
    tags: &id023
    - Artificial Intelligence
    - Meeting Assistant
    - Summary
    - Transcription
    url: /providers/fireflies/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id024
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id025
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.3
    band: emerging
    in_catalog: true
    kin_score: 25.0
    mcp: &id026
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id027
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id028
      status: none
    slug: integrately
    status: profiled
    tags: &id029
    - Automation
    - Business Process Automation
    - No-Code
    - iPaaS
    url: /providers/integrately/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id030
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id031
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.9
    band: developing
    in_catalog: true
    kin_score: 43.5
    mcp: &id032
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id033
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id034
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id035
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.4
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id036
      source: https://docs.n8n.io/advanced-ai/accessing-n8n-mcp-server/
      status: verified
    slug: n8n
    status: profiled
    tags: &id037
    - Agents
    - Artificial Intelligence
    - Integration
    - Workflows
    url: /providers/n8n/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id038
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id039
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id040
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id041
    - Connect
    - Pipedream
    - Pro-Code-API-Composition
    - Workflows
    url: /providers/pipedream/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 25.7
    mcp: &id042
      status: none
    slug: raycast
    status: profiled
    tags: &id043
    - Extensions
    - Launcher
    - Productivity
    - SDK
    url: /providers/raycast/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.1
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id044
      status: none
    slug: reclaim-ai
    status: profiled
    tags: &id045
    - Artificial Intelligence
    - Calendar
    - Productivity
    - Scheduling
    url: /providers/reclaim-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id048
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id049
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: emerging
    in_catalog: true
    kin_score: 23.1
    mcp: &id050
      source: https://help.sunsama.com/docs/integrations/mcp
      status: verified
    slug: sunsama
    status: profiled
    tags: &id051
    - Calendar Integration
    - Company
    - Productivity
    - Task Management
    url: /providers/sunsama/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.2
    mcp: &id052
      source: https://registry.modelcontextprotocol.io/v0/servers?search=toggl
      status: verified
    slug: toggl
    status: profiled
    tags: &id053
    - Billing
    - Productivity
    - Project Management
    - Time Tracking
    url: /providers/toggl/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id054
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id055
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id056
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id057
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id058
      status: none
    slug: zendesk
    status: profiled
    tags: &id059
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id060
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-cliq
    status: profiled
    tags: &id061
    - Bots
    - Chat
    - Messaging
    - Team Collaboration
    url: /providers/zoho-cliq/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 36.4
    mcp: &id062
      status: none
    slug: zoho-mail
    status: profiled
    tags: &id063
    - Collaboration
    - Email
    - Mail
    - Messaging
    url: /providers/zoho-mail/
  layer: common
  name: Zoho Mail
  provider: zoho-mail
  says: lists Zoho Mail as an integration
  source: https://www.todoist.com/integrations/category/all
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/task-todo/todoist/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id002
  name: Akiflow
  slug: akiflow
  status: queued for profiling
  tags: *id003
  url: null
- agent_band: agent-aware
  agent_readiness: 22.5
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id004
  name: Albato
  slug: albato
  status: profiled
  tags: *id005
  url: /providers/albato/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id006
  name: Atlassian Rovo
  slug: atlassian
  status: profiled
  tags: *id007
  url: /providers/atlassian/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id008
  name: ChatGPT app
  slug: openai
  status: profiled
  tags: *id009
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id010
  name: Claude connector
  slug: anthropic
  status: profiled
  tags: *id011
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id012
  name: Everhour
  slug: everhour
  status: profiled
  tags: *id013
  url: /providers/everhour/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id014
  name: Evernote
  slug: evernote
  status: profiled
  tags: *id015
  url: /providers/evernote/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id016
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id017
  url: /providers/facebook/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.0
  mcp: *id018
  name: Fantastical (Flexibits)
  slug: flexibits
  status: profiled
  tags: *id019
  url: /providers/flexibits/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id020
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id021
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 60.4
  band: exemplar
  in_catalog: true
  kin_score: 72.7
  mcp: *id022
  name: Fireflies.ai
  slug: fireflies
  status: profiled
  tags: *id023
  url: /providers/fireflies/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id024
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id025
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 43.3
  band: emerging
  in_catalog: true
  kin_score: 25.0
  mcp: *id026
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id027
  url: /providers/ifttt/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id028
  name: Integrately
  slug: integrately
  status: profiled
  tags: *id029
  url: /providers/integrately/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id030
  name: Jira
  slug: jira
  status: profiled
  tags: *id031
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id032
  name: Make
  slug: make
  status: profiled
  tags: *id033
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id034
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id035
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id036
  name: n8n
  slug: n8n
  status: profiled
  tags: *id037
  url: /providers/n8n/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id038
  name: Outlook / Outlook Calendar
  slug: microsoft-outlook
  status: profiled
  tags: *id039
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id040
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id041
  url: /providers/pipedream/
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 25.7
  mcp: *id042
  name: Raycast
  slug: raycast
  status: profiled
  tags: *id043
  url: /providers/raycast/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id044
  name: Reclaim.ai
  slug: reclaim-ai
  status: profiled
  tags: *id045
  url: /providers/reclaim-ai/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id046
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id047
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id048
  name: Slack
  slug: slack
  status: profiled
  tags: *id049
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: emerging
  in_catalog: true
  kin_score: 23.1
  mcp: *id050
  name: Sunsama
  slug: sunsama
  status: profiled
  tags: *id051
  url: /providers/sunsama/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.2
  mcp: *id052
  name: Toggl Track
  slug: toggl
  status: profiled
  tags: *id053
  url: /providers/toggl/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id054
  name: Trello
  slug: trello
  status: profiled
  tags: *id055
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id056
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id057
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id058
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id059
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id060
  name: Zoho Cliq
  slug: zoho-cliq
  status: profiled
  tags: *id061
  url: /providers/zoho-cliq/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 36.4
  mcp: *id062
  name: Zoho Mail
  slug: zoho-mail
  status: profiled
  tags: *id063
  url: /providers/zoho-mail/
siblings:
- name: Donetick
  rows: 4
  url: /applications/task-todo/donetick/
- name: Super Productivity
  rows: 16
  url: /applications/task-todo/super-productivity/
- name: Tasks.org
  rows: 8
  url: /applications/task-todo/tasks-org/
- name: TickTick
  rows: 14
  url: /applications/task-todo/ticktick/
- name: Vikunja
  rows: 8
  url: /applications/task-todo/vikunja/
sitemap: true
title: 'Todoist: Tasks & To-do Lists reference app'
---
