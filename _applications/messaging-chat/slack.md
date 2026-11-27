---
app: Slack
app_slug: slack
app_url: https://slack.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce Sales Cloud
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Freshdesk
  - Salesforce Service Cloud
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Miro
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - ChatGPT / Codex
  - Claude
  - Writer
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-230.30.20
  key: AE-230.30.20
  layer: domain
  name: Lead Data
  providers:
  - ZoomInfo
  url: /capabilities/company-contact-data/
  via_parent: Company & Contact Data
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  - Jira
  - Notion
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-410.50.30
  key: BC-410.50.30
  layer: domain
  name: Sales Enablement
  providers:
  - Highspot
  url: /capabilities/sales-operations-management/
  via_parent: Sales Operations Management
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-922
  key: AE-922
  layer: domain
  name: Spreadsheets & No-Code Databases
  providers:
  - Google Sheets
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  - AWS Chatbot
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: messaging-chat
  name: Messaging & Team Chat
  url: /applications/messaging-chat/
counts:
  declared: 23
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.Slack/latest/
- route: integrations page
  url: https://slack.com/integrations
integrations:
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
    kin_score: 80.7
    mcp: &id039
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id040
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.Slack/latest/
  tier: observed
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
    mcp: &id001
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id002
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://slack.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 41.1
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id003
      status: none
    slug: amazon-q
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Artificial Intelligence
    - Assistant
    - Enterprise
    url: /providers/amazon-q/
  layer: domain
  name: AWS Chatbot
  provider: amazon-q
  says: lists AWS Chatbot as an integration
  source: https://slack.com/integrations
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
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id005
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://slack.com/integrations
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
    mcp: &id007
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: ChatGPT / Codex
  provider: openai
  says: lists ChatGPT / Codex as an integration
  source: https://slack.com/integrations
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
    mcp: &id009
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id010
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: domain
  name: Claude
  provider: anthropic
  says: lists Claude as an integration
  source: https://slack.com/integrations
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
    mcp: &id011
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id012
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://slack.com/integrations
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
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id013
      status: none
    slug: freshdesk
    status: profiled
    tags: &id014
    - Application
    - Automation
    - Customer Service
    - Help Desk
    url: /providers/freshdesk/
  layer: domain
  name: Freshdesk
  provider: freshdesk
  says: lists Freshdesk as an integration
  source: https://slack.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id015
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://slack.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id017
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id018
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://slack.com/integrations
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
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id019
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id020
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://slack.com/integrations
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
    mcp: &id021
      status: none
    slug: google-sheets
    status: profiled
    tags: &id022
    - Google Workspace
    - Productivity
    - Spreadsheets
    url: /providers/google-sheets/
  layer: domain
  name: Google Sheets
  provider: google-sheets
  says: lists Google Sheets as an integration
  source: https://slack.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-410.50.30
    key: BC-410.50.30
    name: Sales Enablement
    url: /capabilities/sales-operations-management/
    via_parent: Sales Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.2
    band: developing
    in_catalog: true
    kin_score: 45.6
    mcp: &id023
      source: https://mcp.highspot.com/mcp
      status: verified
    slug: highspot
    status: profiled
    tags: &id024
    - CRM Integration
    - Content Management
    - Pitch Analytics
    - Sales Enablement
    url: /providers/highspot/
  layer: domain
  name: Highspot
  provider: highspot
  says: lists Highspot as an integration
  source: https://slack.com/integrations
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
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://slack.com/integrations
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id027
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id028
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://slack.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id029
      source: https://developers.miro.com/docs/miro-mcp
      status: verified
    slug: miro
    status: profiled
    tags: &id030
    - Diagramming
    - Productivity
    - Visual Collaboration
    - Whiteboard
    url: /providers/miro/
  layer: domain
  name: Miro
  provider: miro
  says: lists Miro as an integration
  source: https://slack.com/integrations
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id031
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id032
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://slack.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id033
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id034
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: lists PagerDuty as an integration
  source: https://slack.com/integrations
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
    mcp: &id035
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id036
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce Sales Cloud
  provider: salesforce
  says: lists Salesforce Sales Cloud as an integration
  source: https://slack.com/integrations
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
    agent_band: agent-native
    agent_readiness: 50.0
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id037
      status: none
    slug: service-cloud
    status: profiled
    tags: &id038
    - CRM
    - Cloud
    - Customer Service
    - Enterprise
    url: /providers/service-cloud/
  layer: domain
  name: Salesforce Service Cloud
  provider: service-cloud
  says: lists Salesforce Service Cloud as an integration
  source: https://slack.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 27.1
    band: thin
    in_catalog: true
    kin_score: 35.4
    mcp: &id041
      source: https://github.com/writer/writer-mcp
      status: verified
    slug: writer
    status: profiled
    tags: &id042
    - Artificial Intelligence
    - Content Generation
    - Enterprise
    - LLM
    url: /providers/writer/
  layer: domain
  name: Writer
  provider: writer
  says: lists Writer as an integration
  source: https://slack.com/integrations
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
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
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
  source: https://slack.com/integrations
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
    mcp: &id045
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id046
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://slack.com/integrations
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
    agent_readiness: 63.0
    band: exemplar
    in_catalog: true
    kin_score: 86.8
    mcp: &id047
      source: https://github.com/Zoominfo/zoominfo-mcp-plugin
      status: verified
    slug: zoominfo
    status: profiled
    tags: &id048
    - B2B
    - B2B Data
    - Company Data
    - Contact Database
    url: /providers/zoominfo/
  layer: domain
  name: ZoomInfo
  provider: zoominfo
  says: lists ZoomInfo as an integration
  source: https://slack.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/messaging-chat/slack/
providers:
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id001
  name: Asana
  slug: asana
  status: profiled
  tags: *id002
  url: /providers/asana/
- agent_band: agent-native
  agent_readiness: 41.1
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id003
  name: AWS Chatbot
  slug: amazon-q
  status: profiled
  tags: *id004
  url: /providers/amazon-q/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id005
  name: Box
  slug: box
  status: profiled
  tags: *id006
  url: /providers/box/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id007
  name: ChatGPT / Codex
  slug: openai
  status: profiled
  tags: *id008
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id009
  name: Claude
  slug: anthropic
  status: profiled
  tags: *id010
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id011
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id012
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id013
  name: Freshdesk
  slug: freshdesk
  status: profiled
  tags: *id014
  url: /providers/freshdesk/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id015
  name: GitHub
  slug: github
  status: profiled
  tags: *id016
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id017
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id018
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id019
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id020
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id021
  name: Google Sheets
  slug: google-sheets
  status: profiled
  tags: *id022
  url: /providers/google-sheets/
- agent_band: agent-ready
  agent_readiness: 29.2
  band: developing
  in_catalog: true
  kin_score: 45.6
  mcp: *id023
  name: Highspot
  slug: highspot
  status: profiled
  tags: *id024
  url: /providers/highspot/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id025
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id026
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id027
  name: Jira
  slug: jira
  status: profiled
  tags: *id028
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id029
  name: Miro
  slug: miro
  status: profiled
  tags: *id030
  url: /providers/miro/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id031
  name: Notion
  slug: notion
  status: profiled
  tags: *id032
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id033
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id034
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id035
  name: Salesforce Sales Cloud
  slug: salesforce
  status: profiled
  tags: *id036
  url: /providers/salesforce/
- agent_band: agent-native
  agent_readiness: 50.0
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id037
  name: Salesforce Service Cloud
  slug: service-cloud
  status: profiled
  tags: *id038
  url: /providers/service-cloud/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id039
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id040
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: thin
  in_catalog: true
  kin_score: 35.4
  mcp: *id041
  name: Writer
  slug: writer
  status: profiled
  tags: *id042
  url: /providers/writer/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id043
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id044
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id045
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id046
  url: /providers/zoom/
- agent_band: agent-ready
  agent_readiness: 63.0
  band: exemplar
  in_catalog: true
  kin_score: 86.8
  mcp: *id047
  name: ZoomInfo
  slug: zoominfo
  status: profiled
  tags: *id048
  url: /providers/zoominfo/
siblings:
- name: Discord
  rows: 23
  url: /applications/messaging-chat/discord/
- name: Element / Matrix (Synapse)
  rows: 4
  url: /applications/messaging-chat/element-matrix-synapse/
- name: Mattermost
  rows: 25
  url: /applications/messaging-chat/mattermost/
- name: Rocket.Chat
  rows: 11
  url: /applications/messaging-chat/rocket-chat/
- name: Signal
  rows: 7
  url: /applications/messaging-chat/signal/
- name: Zulip
  rows: 11
  url: /applications/messaging-chat/zulip/
sitemap: true
title: 'Slack: Messaging & Team Chat reference app'
---
