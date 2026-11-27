---
app: ConfigCat
app_slug: configcat
app_url: https://configcat.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - Bitrise
  - CircleCI
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.20.10
  key: BC-4210.20.10
  layer: domain
  name: Environment Provisioning
  providers:
  - Terraform
  url: /capabilities/environment-management/
  via_parent: Environment Management
- attribution: API Evangelist extension
  id: AE-905
  key: AE-905
  layer: domain
  name: IDEs & AI Coding Assistants
  providers:
  - JetBrains IntelliJ
  - VS Code
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Amplitude
  - Google Analytics
  - Mixpanel
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Bitbucket
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Twilio Segment
  url: /capabilities/customer-data-management/
  via_parent: null
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira
  - monday.com
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  - Zoho Flow
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 18
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://configcat.com/docs/integrations/overview/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: domain
  name: Amplitude
  provider: amplitude
  says: lists Amplitude as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
    mcp: &id003
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id004
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: lists Bitbucket as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.0
    band: minimal
    in_catalog: true
    kin_score: 5.1
    mcp: &id005
      source: https://github.com/bitrise-io/bitrise-mcp
      status: verified
    slug: bitrise
    status: profiled
    tags: &id006
    - Continuous Integration
    - Developer Tools
    - Public APIs
    url: /providers/bitrise/
  layer: domain
  name: Bitrise
  provider: bitrise
  says: lists Bitrise as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 73.5
    mcp: &id007
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id008
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
  layer: domain
  name: CircleCI
  provider: circleci
  says: lists CircleCI as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id009
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id010
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id011
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id013
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id014
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: domain
  name: Google Analytics
  provider: google-analytics
  says: lists Google Analytics as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-905
    key: AE-905
    name: IDEs & AI Coding Assistants
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.1
    band: developing
    in_catalog: true
    kin_score: 54.0
    mcp: &id015
      source: https://github.com/JetBrains/mcp-server-plugin
      status: verified
    slug: jetbrains
    status: profiled
    tags: &id016
    - CI/CD
    - Developer Tools
    - IDE
    - JetBrains
    url: /providers/jetbrains/
  layer: domain
  name: JetBrains IntelliJ
  provider: jetbrains
  says: lists JetBrains IntelliJ as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id017
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id018
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.7
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id019
      source: https://docs.mixpanel.com/docs/features/mcp
      status: verified
    slug: mixpanel
    status: profiled
    tags: &id020
    - Analytics
    - Data Analysis
    - Event Tracking
    - Product Analytics
    url: /providers/mixpanel/
  layer: domain
  name: Mixpanel
  provider: mixpanel
  says: lists Mixpanel as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id021
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id022
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: common
  name: monday.com
  provider: monday-com
  says: lists monday.com as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id023
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id024
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.20.10
    key: BC-4210.20.10
    name: Environment Provisioning
    url: /capabilities/environment-management/
    via_parent: Environment Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id025
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id026
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
  layer: domain
  name: Terraform
  provider: terraform
  says: lists Terraform as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id027
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id028
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: common
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id029
      status: none
    slug: segment
    status: profiled
    tags: &id030
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Twilio Segment
  provider: segment
  says: lists Twilio Segment as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-905
    key: AE-905
    name: IDEs & AI Coding Assistants
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 25.9
    mcp: &id031
      status: none
    slug: visual-studio-code
    status: profiled
    tags: &id032
    - Code Editor
    - Developer Tools
    - IDE
    - Open Source
    url: /providers/visual-studio-code/
  layer: domain
  name: VS Code
  provider: visual-studio-code
  says: lists VS Code as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    mcp: &id033
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id034
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://configcat.com/docs/integrations/overview/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id035
      status: unchecked
    slug: zoho-flow
    status: queued for profiling
    tags: &id036 []
    url: null
  layer: common
  name: Zoho Flow
  provider: zoho-flow
  says: lists Zoho Flow as an integration
  source: https://configcat.com/docs/integrations/overview/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/configcat/
providers:
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id003
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id004
  url: /providers/bitbucket/
- agent_band: agent-aware
  agent_readiness: 12.0
  band: minimal
  in_catalog: true
  kin_score: 5.1
  mcp: *id005
  name: Bitrise
  slug: bitrise
  status: profiled
  tags: *id006
  url: /providers/bitrise/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 73.5
  mcp: *id007
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id008
  url: /providers/circleci/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id009
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id010
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id011
  name: GitHub
  slug: github
  status: profiled
  tags: *id012
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id013
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id014
  url: /providers/google-analytics/
- agent_band: agent-ready
  agent_readiness: 30.1
  band: developing
  in_catalog: true
  kin_score: 54.0
  mcp: *id015
  name: JetBrains IntelliJ
  slug: jetbrains
  status: profiled
  tags: *id016
  url: /providers/jetbrains/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id017
  name: Jira
  slug: jira
  status: profiled
  tags: *id018
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 47.7
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id019
  name: Mixpanel
  slug: mixpanel
  status: profiled
  tags: *id020
  url: /providers/mixpanel/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id021
  name: monday.com
  slug: monday-com
  status: profiled
  tags: *id022
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id023
  name: Slack
  slug: slack
  status: profiled
  tags: *id024
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id025
  name: Terraform
  slug: terraform
  status: profiled
  tags: *id026
  url: /providers/terraform/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id027
  name: Trello
  slug: trello
  status: profiled
  tags: *id028
  url: /providers/trello/
- agent_band: agent-aware
  agent_readiness: 27.7
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id029
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id030
  url: /providers/segment/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 25.9
  mcp: *id031
  name: VS Code
  slug: visual-studio-code
  status: profiled
  tags: *id032
  url: /providers/visual-studio-code/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id033
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id034
  url: /providers/zapier/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id035
  name: Zoho Flow
  slug: zoho-flow
  status: queued for profiling
  tags: *id036
  url: null
siblings:
- name: Flagsmith
  rows: 16
  url: /applications/feature-flags-experimentation/flagsmith/
- name: Flipt
  rows: 7
  url: /applications/feature-flags-experimentation/flipt/
- name: GrowthBook
  rows: 20
  url: /applications/feature-flags-experimentation/growthbook/
- name: LaunchDarkly
  rows: 91
  url: /applications/feature-flags-experimentation/launchdarkly/
- name: Statsig
  rows: 33
  url: /applications/feature-flags-experimentation/statsig/
- name: Unleash
  rows: 4
  url: /applications/feature-flags-experimentation/unleash/
sitemap: true
title: 'ConfigCat: Feature Flags & Experimentation reference app'
---
