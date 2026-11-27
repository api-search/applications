---
app: Harvest
app_slug: harvest
app_url: https://www.getharvest.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Databox
  - Klipfolio
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - Deel
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.50
  key: invoice-generation-management
  layer: domain
  name: Invoice Generation Management
  providers:
  - QuickBooks Online
  - Xero
  url: /capabilities/invoice-generation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.70.20
  key: BC-300.70.20
  layer: domain
  name: Payroll Administration
  providers:
  - Gusto
  url: /capabilities/hr-operations-management/
  via_parent: HR Operations Management
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  - Basecamp
  - ClickUp
  - Jira
  - Linear
  - Monday.com
  - Notion
  - Teamwork Projects
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.10.10
  key: BC-4330.10.10
  layer: domain
  name: Time Entry Capture
  providers:
  - Freshservice
  - GitHub
  - Zendesk
  - Zoho Desk
  url: /capabilities/timekeeping-management/
  via_parent: Timekeeping Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  - Outlook.com
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Bugsnag
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - IFTTT
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: time-tracking
  name: Time Tracking & Timesheets
  url: /applications/time-tracking/
counts:
  declared: 27
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.harvestapp/latest/
- route: integrations page
  url: https://www.getharvest.com/integrations
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 76.3
    mcp: &id005
      source: https://github.com/SmartBear/smartbear-mcp
      status: verified
    slug: bugsnag
    status: profiled
    tags: &id006
    - Application Performance Monitoring
    - Error Monitoring
    - Monitoring
    - Observability
    url: /providers/bugsnag/
  layer: common
  name: Bugsnag
  provider: bugsnag
  says: ships the Bugsnag SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.harvestapp/latest/
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
  source: https://www.getharvest.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 24.9
    band: developing
    in_catalog: true
    kin_score: 49.0
    mcp: &id003
      source: https://github.com/basecamp/mcp
      status: verified
    slug: basecamp
    status: profiled
    tags: &id004
    - Collaboration
    - Project Management
    - REST
    - Software-as-a-Service
    url: /providers/basecamp/
  layer: domain
  name: Basecamp
  provider: basecamp
  says: lists Basecamp as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id007
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id008
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: domain
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://www.getharvest.com/integrations
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
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id009
      source: https://github.com/databox/databox-mcp
      status: verified
    slug: databox
    status: profiled
    tags: &id010
    - Analytics
    - Artificial Intelligence
    - Company
    - Data Integration
    url: /providers/databox/
  layer: domain
  name: Databox
  provider: databox
  says: lists Databox as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 52.0
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id011
      source: https://developer.deel.com/docs/mcp
      status: documented
    slug: deel-com
    status: profiled
    tags: &id012
    - Employer of Record
    - Global Payroll
    - Human Resources
    - Payroll
    url: /providers/deel-com/
  layer: domain
  name: Deel
  provider: deel-com
  says: lists Deel as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10.10
    key: BC-4330.10.10
    name: Time Entry Capture
    url: /capabilities/timekeeping-management/
    via_parent: Timekeeping Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id013
      status: none
    slug: freshservice
    status: profiled
    tags: &id014
    - Asset Management
    - Help Desk
    - ITSM
    - Ticketing
    url: /providers/freshservice/
  layer: domain
  name: Freshservice
  provider: freshservice
  says: lists Freshservice as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10.10
    key: BC-4330.10.10
    name: Time Entry Capture
    url: /capabilities/timekeeping-management/
    via_parent: Timekeeping Management
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
  source: https://www.getharvest.com/integrations
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
    mcp: &id017
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id018
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70.20
    key: BC-300.70.20
    name: Payroll Administration
    url: /capabilities/hr-operations-management/
    via_parent: HR Operations Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id019
      status: none
    slug: gusto
    status: profiled
    tags: &id020
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: domain
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://www.getharvest.com/integrations
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
    agent_readiness: 42.4
    band: emerging
    in_catalog: true
    kin_score: 24.1
    mcp: &id021
      source: https://github.com/IFTTT/ifttt-plugins
      status: verified
    slug: ifttt
    status: profiled
    tags: &id022
    - Automation
    - No-Code
    - Webhook
    - iPaaS
    url: /providers/ifttt/
  layer: common
  name: IFTTT
  provider: ifttt
  says: lists IFTTT as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id023
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id024
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://www.getharvest.com/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: klipfolio
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: Klipfolio
  provider: klipfolio
  says: lists Klipfolio as an integration
  source: https://www.getharvest.com/integrations
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
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id027
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id028
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id029
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id030
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id031
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id032
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: domain
  name: Monday.com
  provider: monday-com
  says: lists Monday.com as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id033
      source: https://developers.notion.com/docs/mcp
      status: verified
    slug: notion
    status: profiled
    tags: &id034
    - Collaboration
    - Database
    - Ideas
    - Notes
    url: /providers/notion/
  layer: domain
  name: Notion
  provider: notion
  says: lists Notion as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id035
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id036
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Outlook.com
  provider: microsoft-outlook
  says: lists Outlook.com as an integration
  source: https://www.getharvest.com/integrations
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id037
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id038
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: lists PayPal as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id039
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id040
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online
  provider: quickbooks
  says: lists QuickBooks Online as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id041
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id042
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id043
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id044
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: lists Stripe as an integration
  source: https://www.getharvest.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id045
      source: https://github.com/Teamwork/mcp
      status: verified
    slug: teamwork
    status: profiled
    tags: &id046
    - Client Services
    - Project Management
    - Task Management
    - Time Tracking
    url: /providers/teamwork/
  layer: domain
  name: Teamwork Projects
  provider: teamwork
  says: lists Teamwork Projects as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id047
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id048
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.50
    key: invoice-generation-management
    name: Invoice Generation Management
    url: /capabilities/invoice-generation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id049
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id050
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.getharvest.com/integrations
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
    mcp: &id051
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id052
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10.10
    key: BC-4330.10.10
    name: Time Entry Capture
    url: /capabilities/timekeeping-management/
    via_parent: Timekeeping Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id053
      status: none
    slug: zendesk
    status: profiled
    tags: &id054
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk
  provider: zendesk
  says: lists Zendesk as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10.10
    key: BC-4330.10.10
    name: Time Entry Capture
    url: /capabilities/timekeeping-management/
    via_parent: Timekeeping Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: thin
    in_catalog: true
    kin_score: 28.2
    mcp: &id055
      source: https://www.zoho.com/mcp/
      status: verified
    slug: zoho-desk
    status: profiled
    tags: &id056
    - Customer Service
    - Help Desk
    - Knowledge Base
    - Ticketing
    url: /providers/zoho-desk/
  layer: domain
  name: Zoho Desk
  provider: zoho-desk
  says: lists Zoho Desk as an integration
  source: https://www.getharvest.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/time-tracking/harvest/
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
- agent_band: agent-aware
  agent_readiness: 24.9
  band: developing
  in_catalog: true
  kin_score: 49.0
  mcp: *id003
  name: Basecamp
  slug: basecamp
  status: profiled
  tags: *id004
  url: /providers/basecamp/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 76.3
  mcp: *id005
  name: Bugsnag
  slug: bugsnag
  status: profiled
  tags: *id006
  url: /providers/bugsnag/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id007
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id008
  url: /providers/clickup/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id009
  name: Databox
  slug: databox
  status: profiled
  tags: *id010
  url: /providers/databox/
- agent_band: agent-native
  agent_readiness: 52.0
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id011
  name: Deel
  slug: deel-com
  status: profiled
  tags: *id012
  url: /providers/deel-com/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id013
  name: Freshservice
  slug: freshservice
  status: profiled
  tags: *id014
  url: /providers/freshservice/
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
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 64.6
  mcp: *id017
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id018
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id019
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id020
  url: /providers/gusto/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: emerging
  in_catalog: true
  kin_score: 24.1
  mcp: *id021
  name: IFTTT
  slug: ifttt
  status: profiled
  tags: *id022
  url: /providers/ifttt/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id023
  name: Jira
  slug: jira
  status: profiled
  tags: *id024
  url: /providers/jira/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: Klipfolio
  slug: klipfolio
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id027
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id028
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id029
  name: Make
  slug: make
  status: profiled
  tags: *id030
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id031
  name: Monday.com
  slug: monday-com
  status: profiled
  tags: *id032
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id033
  name: Notion
  slug: notion
  status: profiled
  tags: *id034
  url: /providers/notion/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id035
  name: Outlook.com
  slug: microsoft-outlook
  status: profiled
  tags: *id036
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id037
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id038
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id039
  name: QuickBooks Online
  slug: quickbooks
  status: profiled
  tags: *id040
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id041
  name: Slack
  slug: slack
  status: profiled
  tags: *id042
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id043
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id044
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id045
  name: Teamwork Projects
  slug: teamwork
  status: profiled
  tags: *id046
  url: /providers/teamwork/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id047
  name: Trello
  slug: trello
  status: profiled
  tags: *id048
  url: /providers/trello/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id049
  name: Xero
  slug: xero
  status: profiled
  tags: *id050
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id051
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id052
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id053
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id054
  url: /providers/zendesk/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: thin
  in_catalog: true
  kin_score: 28.2
  mcp: *id055
  name: Zoho Desk
  slug: zoho-desk
  status: profiled
  tags: *id056
  url: /providers/zoho-desk/
siblings:
- name: Clockify
  rows: 29
  url: /applications/time-tracking/clockify/
- name: Kimai
  rows: 3
  url: /applications/time-tracking/kimai/
- name: solidtime
  rows: 3
  url: /applications/time-tracking/solidtime/
- name: Super Productivity
  rows: 16
  url: /applications/time-tracking/super-productivity/
- name: Toggl Track
  rows: 24
  url: /applications/time-tracking/toggl-track/
sitemap: true
title: 'Harvest: Time Tracking & Timesheets reference app'
---
