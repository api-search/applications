---
app: Lokalise
app_slug: lokalise
app_url: https://lokalise.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.70
  key: AE-170.70
  layer: domain
  name: Content Management
  providers:
  - Contentful
  - Contentstack
  - Hygraph
  - Storyblok
  - Webflow
  - WordPress
  url: /capabilities/content-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4260.40
  key: customer-lifecycle-engagement
  layer: domain
  name: Customer Lifecycle Engagement
  providers:
  - Braze
  - Customer.io
  - Iterable
  - MoEngage
  url: /capabilities/customer-lifecycle-engagement/
  via_parent: null
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: domain
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Salesforce CRM / Knowledge
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: domain
  name: Customer Service Management
  providers:
  - Intercom Articles
  - Zendesk Guide
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: domain
  name: Design & Creative Editing
  providers:
  - Ditto (dittowords.com)
  - Figma
  - Sketch
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Mailchimp
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Azure Repos
  - Bitbucket
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
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
  - Asana
  - Jira
  - TimeCamp
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: translation
  name: Translation & Localization
  url: /applications/translation/
counts:
  declared: 32
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://lokalise.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: lists Amazon S3 as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id003
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id004
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id005
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id006
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure Repos
  provider: microsoft-azure-devops
  says: lists Azure Repos as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id007
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id008
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: lists Bitbucket as an integration
  source: https://lokalise.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id009
      source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
      status: verified
    slug: braze
    status: profiled
    tags: &id010
    - Customer Engagement
    - Marketing Automation
    - Messaging
    - Push Notifications
    url: /providers/braze/
  layer: domain
  name: Braze
  provider: braze
  says: lists Braze as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 56.5
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id011
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id012
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
  layer: domain
  name: Contentful
  provider: contentful
  says: lists Contentful as an integration
  source: https://lokalise.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 26.6
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id013
      source: https://registry.npmjs.org/@contentstack/mcp
      status: verified
    slug: contentstack
    status: profiled
    tags: &id014
    - Content Delivery
    - Content Management
    - Digital Experience
    - Headless CMS
    url: /providers/contentstack/
  layer: domain
  name: Contentstack
  provider: contentstack
  says: lists Contentstack as an integration
  source: https://lokalise.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 69.9
    band: exemplar
    in_catalog: true
    kin_score: 86.9
    mcp: &id015
      source: https://github.com/customerio/claude-plugin
      status: verified
    slug: customer-io
    status: profiled
    tags: &id016
    - Behavioral Data
    - Broadcast
    - CDP
    - Campaigns
    url: /providers/customer-io/
  layer: domain
  name: Customer.io
  provider: customer-io
  says: lists Customer.io as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id017
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id018
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 42.2
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id019
      source: https://developer.dittowords.com/mcp-reference/overview
      status: verified
    slug: dittowords
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Company
    - Content
    - Localization
    url: /providers/dittowords/
  layer: domain
  name: Ditto (dittowords.com)
  provider: dittowords
  says: lists Ditto (dittowords.com) as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 57.8
    band: strong
    in_catalog: true
    kin_score: 65.6
    mcp: &id021
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id022
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
  layer: domain
  name: Figma
  provider: figma
  says: lists Figma as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id023
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id024
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id025
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id026
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://lokalise.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id027
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id028
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: lists Google Cloud Storage as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id029
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id030
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 42.8
    band: emerging
    in_catalog: true
    kin_score: 22.2
    mcp: &id031
      status: none
    slug: hygraph
    status: profiled
    tags: &id032
    - Content Federation
    - Content Management
    - GraphQL
    - Headless CMS
    url: /providers/hygraph/
  layer: domain
  name: Hygraph
  provider: hygraph
  says: lists Hygraph as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id033
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id034
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: domain
  name: Intercom Articles
  provider: intercom
  says: lists Intercom Articles as an integration
  source: https://lokalise.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: exemplar
    in_catalog: true
    kin_score: 67.9
    mcp: &id035
      source: https://github.com/Iterable/mcp-server
      status: verified
    slug: iterable
    status: profiled
    tags: &id036
    - Cross-Channel Messaging
    - Customer Engagement
    - Email
    - Marketing Automation
    url: /providers/iterable/
  layer: domain
  name: Iterable
  provider: iterable
  says: lists Iterable as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id037
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id038
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 42.3
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id039
      status: none
    slug: mailchimp
    status: profiled
    tags: &id040
    - Campaigns
    - Email Marketing
    - Marketing Automation
    - Newsletters
    url: /providers/mailchimp/
  layer: domain
  name: Mailchimp
  provider: mailchimp
  says: lists Mailchimp as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id041
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id042
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://lokalise.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id043
      status: none
    slug: moengage
    status: profiled
    tags: &id044
    - Customer Data Platform
    - Customer Engagement
    - Marketing Automation
    - Push Notifications
    url: /providers/moengage/
  layer: domain
  name: MoEngage
  provider: moengage
  says: lists MoEngage as an integration
  source: https://lokalise.com/integrations
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
  name: Salesforce CRM / Knowledge
  provider: salesforce
  says: lists Salesforce CRM / Knowledge as an integration
  source: https://lokalise.com/integrations
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 17.1
    mcp: &id047
      source: https://github.com/sketch-hq/sketch-mcp-bundle
      status: verified
    slug: sketch
    status: profiled
    tags: &id048
    - Collaboration
    - Design
    - Prototyping
    - Workspace
    url: /providers/sketch/
  layer: domain
  name: Sketch
  provider: sketch
  says: lists Sketch as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id049
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id050
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id051
      source: https://github.com/storyblok/mcp-server
      status: verified
    slug: storyblok
    status: profiled
    tags: &id052
    - CMS
    - Content Delivery
    - Content Management
    - Headless CMS
    url: /providers/storyblok/
  layer: domain
  name: Storyblok
  provider: storyblok
  says: lists Storyblok as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 50.5
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id053
      status: none
    slug: timecamp
    status: profiled
    tags: &id054
    - Attendance
    - Productivity
    - Time Tracking
    - Timesheets
    url: /providers/timecamp/
  layer: common
  name: TimeCamp
  provider: timecamp
  says: lists TimeCamp as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id055
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id056
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: common
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 62.5
    band: strong
    in_catalog: true
    kin_score: 60.7
    mcp: &id057
      source: https://developers.webflow.com/mcp/reference/overview
      status: verified
    slug: webflow
    status: profiled
    tags: &id058
    - CMS
    - E-Commerce
    - No-Code
    - Web Development
    url: /providers/webflow/
  layer: domain
  name: Webflow
  provider: webflow
  says: lists Webflow as an integration
  source: https://lokalise.com/integrations
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
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 46.0
    mcp: &id059
      source: https://github.com/WordPress/mcp-adapter
      status: verified
    slug: wordpress
    status: profiled
    tags: &id060
    - CMS
    - Content Management
    - Open Source
    - WordPress
    url: /providers/wordpress/
  layer: domain
  name: WordPress
  provider: wordpress
  says: lists WordPress as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id061
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id062
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://lokalise.com/integrations
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
    mcp: &id063
      status: none
    slug: zendesk
    status: profiled
    tags: &id064
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: domain
  name: Zendesk Guide
  provider: zendesk
  says: lists Zendesk Guide as an integration
  source: https://lokalise.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/translation/lokalise/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id003
  name: Asana
  slug: asana
  status: profiled
  tags: *id004
  url: /providers/asana/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id005
  name: Azure Repos
  slug: microsoft-azure-devops
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id007
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id008
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id009
  name: Braze
  slug: braze
  status: profiled
  tags: *id010
  url: /providers/braze/
- agent_band: agent-ready
  agent_readiness: 56.5
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id011
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id012
  url: /providers/contentful/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id013
  name: Contentstack
  slug: contentstack
  status: profiled
  tags: *id014
  url: /providers/contentstack/
- agent_band: agent-ready
  agent_readiness: 69.9
  band: exemplar
  in_catalog: true
  kin_score: 86.9
  mcp: *id015
  name: Customer.io
  slug: customer-io
  status: profiled
  tags: *id016
  url: /providers/customer-io/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id017
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id018
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id019
  name: Ditto (dittowords.com)
  slug: dittowords
  status: profiled
  tags: *id020
  url: /providers/dittowords/
- agent_band: agent-ready
  agent_readiness: 57.8
  band: strong
  in_catalog: true
  kin_score: 65.6
  mcp: *id021
  name: Figma
  slug: figma
  status: profiled
  tags: *id022
  url: /providers/figma/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id023
  name: GitHub
  slug: github
  status: profiled
  tags: *id024
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id025
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id026
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id027
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id028
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 52.7
  band: exemplar
  in_catalog: true
  kin_score: 94.6
  mcp: *id029
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id030
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 42.8
  band: emerging
  in_catalog: true
  kin_score: 22.2
  mcp: *id031
  name: Hygraph
  slug: hygraph
  status: profiled
  tags: *id032
  url: /providers/hygraph/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id033
  name: Intercom Articles
  slug: intercom
  status: profiled
  tags: *id034
  url: /providers/intercom/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: exemplar
  in_catalog: true
  kin_score: 67.9
  mcp: *id035
  name: Iterable
  slug: iterable
  status: profiled
  tags: *id036
  url: /providers/iterable/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id037
  name: Jira
  slug: jira
  status: profiled
  tags: *id038
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id039
  name: Mailchimp
  slug: mailchimp
  status: profiled
  tags: *id040
  url: /providers/mailchimp/
- agent_band: agent-ready
  agent_readiness: 43.9
  band: developing
  in_catalog: true
  kin_score: 43.5
  mcp: *id041
  name: Make
  slug: make
  status: profiled
  tags: *id042
  url: /providers/make/
- agent_band: agent-native
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id043
  name: MoEngage
  slug: moengage
  status: profiled
  tags: *id044
  url: /providers/moengage/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id045
  name: Salesforce CRM / Knowledge
  slug: salesforce
  status: profiled
  tags: *id046
  url: /providers/salesforce/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 17.1
  mcp: *id047
  name: Sketch
  slug: sketch
  status: profiled
  tags: *id048
  url: /providers/sketch/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id049
  name: Slack
  slug: slack
  status: profiled
  tags: *id050
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id051
  name: Storyblok
  slug: storyblok
  status: profiled
  tags: *id052
  url: /providers/storyblok/
- agent_band: agent-ready
  agent_readiness: 50.5
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id053
  name: TimeCamp
  slug: timecamp
  status: profiled
  tags: *id054
  url: /providers/timecamp/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id055
  name: Trello
  slug: trello
  status: profiled
  tags: *id056
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 62.5
  band: strong
  in_catalog: true
  kin_score: 60.7
  mcp: *id057
  name: Webflow
  slug: webflow
  status: profiled
  tags: *id058
  url: /providers/webflow/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 46.0
  mcp: *id059
  name: WordPress
  slug: wordpress
  status: profiled
  tags: *id060
  url: /providers/wordpress/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id061
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id062
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id063
  name: Zendesk Guide
  slug: zendesk
  status: profiled
  tags: *id064
  url: /providers/zendesk/
siblings:
- name: Crowdin
  rows: 11
  url: /applications/translation/crowdin/
- name: DeepL
  rows: 9
  url: /applications/translation/deepl/
- name: LibreTranslate
  rows: 0
  url: /applications/translation/libretranslate/
- name: Pontoon
  rows: 13
  url: /applications/translation/pontoon/
- name: Tolgee
  rows: 17
  url: /applications/translation/tolgee/
- name: Weblate
  rows: 33
  url: /applications/translation/weblate/
sitemap: true
title: 'Lokalise: Translation & Localization reference app'
---
