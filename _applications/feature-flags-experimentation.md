---
access: understanding
agent_layer:
- app: Statsig
  finding: 'Statsig documents its own MCP server (docs nav: integrations/mcp/overview, tool-reference, Claude Code / Cursor / Codex setup)'
  source: https://docs.statsig.com/integrations/introduction
  tier: declared
- app: GrowthBook
  finding: 'bring-your-own LLM: Vercel AI SDK providers for OpenAI, Anthropic, Google, Mistral and xAI ship in the back end'
  source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  tier: observed
apps:
- anchor: launchdarkly
  counts:
    declared: 91
    observed: 0
  evidence:
  - route: integrations page
    url: https://github.com/launchdarkly/integration-framework/tree/main/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Akamai
    provider: akamai
    says: lists Akamai as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: lists Amazon DynamoDB as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Amazon Kinesis
    provider: kinesis
    says: lists Amazon Kinesis as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: lists Amazon Redshift as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Ansible
    provider: ansible
    says: lists Ansible as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: AppDynamics
    provider: appdynamics
    says: lists AppDynamics as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.30
      key: developer-portal-management
      name: Developer Portal Management
      url: /capabilities/developer-portal-management/
      via_parent: null
    credit: null
    layer: domain
    name: Atlassian Compass
    provider: atlassian-compass
    says: lists Atlassian Compass as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: AWS CloudTrail
    provider: amazon-cloudtrail
    says: lists AWS CloudTrail as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: lists Azure DevOps as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Azure Event Hubs
    provider: microsoft-azure-event-hubs
    says: lists Azure Event Hubs as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitrise
    provider: bitrise
    says: lists Bitrise as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Census
    provider: getcensus
    says: lists Census as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Chronosphere
    provider: chronosphere
    says: lists Chronosphere as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: CircleCI
    provider: circleci
    says: lists CircleCI as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: lists ClickHouse as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Cloudflare
    provider: cloudflare
    says: lists Cloudflare as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1040.40
      key: asset-information-management
      name: Asset Information Management
      url: /capabilities/asset-information-management/
      via_parent: null
    credit: null
    layer: common
    name: CloudQuery
    provider: cloudquery
    says: lists CloudQuery as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    credit: null
    layer: common
    name: Confluence
    provider: confluence
    says: lists Confluence as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3700
      key: content-origination-production-management
      name: Content Origination & Production Management
      url: /capabilities/content-origination-production-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contentful
    provider: contentful
    says: lists Contentful as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Convex
    provider: convex
    says: lists Convex as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.30
      key: developer-portal-management
      name: Developer Portal Management
      url: /capabilities/developer-portal-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cortex
    provider: cortex-idp
    says: lists Cortex as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Crossplane
    provider: crossplane
    says: lists Crossplane as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: lists Databricks as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: domain
    name: Devin (Cognition)
    provider: cognition-labs
    says: lists Devin (Cognition) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3700
      key: content-origination-production-management
      name: Content Origination & Production Management
      url: /capabilities/content-origination-production-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ditto (dittowords.com)
    provider: dittowords
    says: lists Ditto (dittowords.com) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Dynatrace
    provider: dynatrace
    says: lists Dynatrace as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Elastic
    provider: elastic
    says: lists Elastic as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Fastly
    provider: fastly
    says: lists Fastly as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Fulcrum (getfulcrum.io)
    provider: getfulcrum
    says: lists Fulcrum (getfulcrum.io) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: FullStory
    provider: fullstory
    says: lists FullStory as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gitar
    provider: gitar
    says: lists Gitar as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
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
    says: lists GitHub as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub Actions
    provider: github
    says: lists GitHub Actions as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
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
    says: lists GitLab as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: lists Google BigQuery as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Google Cloud Pub/Sub
    provider: google-cloud-pubsub
    says: lists Google Cloud Pub/Sub as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Grafana
    provider: grafana-com
    says: lists Grafana as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Heap
    provider: heap
    says: lists Heap as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Hightouch
    provider: hightouch
    says: lists Hightouch as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Honeycomb
    provider: honeycomb
    says: lists Honeycomb as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: domain
    name: JetBrains IntelliJ
    provider: jetbrains
    says: lists JetBrains IntelliJ as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Kosli
    provider: kosli
    says: lists Kosli as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Last9
    provider: last9
    says: lists Last9 as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Liquibase
    provider: liquibase
    says: lists Liquibase as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Mattermost
    provider: mattermost
    says: lists Mattermost as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Mezmo (LogDNA)
    provider: mezmo
    says: lists Mezmo (LogDNA) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: lists Microsoft Entra ID as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: mParticle
    provider: mparticle
    says: lists mParticle as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Netlify
    provider: netlify
    says: lists Netlify as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: New Relic
    provider: new-relic
    says: lists New Relic as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: ngrok
    provider: ngrok
    says: lists ngrok as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Okteto
    provider: okteto
    says: lists Okteto as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: OneLogin
    provider: onelogin
    says: lists OneLogin as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-130.50
      key: privacy-data-protection-management
      name: Privacy & Data Protection Management
      url: /capabilities/privacy-data-protection-management/
      via_parent: null
    credit: null
    layer: common
    name: Osano
    provider: osano
    says: lists Osano as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: PagerDuty
    provider: pagerduty
    says: lists PagerDuty as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pendo
    provider: pendoio
    says: lists Pendo as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.30
      key: developer-portal-management
      name: Developer Portal Management
      url: /capabilities/developer-portal-management/
      via_parent: null
    credit: null
    layer: domain
    name: Port
    provider: port-io
    says: lists Port as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Release (releaseapp.io)
    provider: release
    says: lists Release (releaseapp.io) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1040.40
      key: asset-information-management
      name: Asset Information Management
      url: /capabilities/asset-information-management/
      via_parent: null
    credit: null
    layer: common
    name: Resmo
    provider: resmo
    says: lists Resmo as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4270.30
      key: developer-portal-management
      name: Developer Portal Management
      url: /capabilities/developer-portal-management/
      via_parent: null
    credit: null
    layer: domain
    name: Roadie
    provider: roadie-io
    says: lists Roadie as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: RudderStack
    provider: rudderstack
    says: lists RudderStack as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
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
    says: lists Sentry as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: SignalFx (Splunk Observability)
    provider: splunk-observability
    says: lists SignalFx (Splunk Observability) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sleuth
    provider: sleuth
    says: lists Sleuth as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Snowplow
    provider: snowplow
    says: lists Snowplow as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: SolarWinds AppOptics
    provider: solarwinds
    says: lists SolarWinds AppOptics as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: domain
    name: Split (Harness FME)
    provider: split
    says: lists Split (Harness FME) as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Splunk
    provider: splunk
    says: lists Splunk as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Sprig
    provider: sprig
    says: lists Sprig as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: domain
    name: Statsig
    provider: statsig
    says: lists Statsig as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Tealium
    provider: tealium
    says: lists Tealium as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Terraform
    provider: terraform
    says: lists Terraform as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
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
    name: Tray.ai
    provider: tray-ai
    says: lists Tray.ai as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: domain
    name: Unleash
    provider: unleash
    says: lists Unleash as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Vercel
    provider: vercel
    says: lists Vercel as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: domain
    name: VS Code
    provider: visual-studio-code
    says: lists VS Code as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
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
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Zendesk
    provider: zendesk
    says: lists Zendesk as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Zeotap
    provider: zeotap
    says: lists Zeotap as an integration
    source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
    tier: declared
  kind: commercial
  name: LaunchDarkly
  page: /applications/feature-flags-experimentation/launchdarkly/
  slug: launchdarkly
  url: https://launchdarkly.com/
- anchor: unleash
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: dependency manifest
    url: https://github.com/Unleash/unleash/blob/main/package.json
  - route: source code
    url: https://github.com/Unleash/unleash/tree/main/src/lib/addons
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
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Microsoft Teams
    provider: microsoft-teams
    says: ships the Microsoft Teams SDK or integration code
    source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/Unleash/unleash/tree/main/src/lib/addons
    tier: observed
  kind: self-hosted
  name: Unleash
  page: /applications/feature-flags-experimentation/unleash/
  slug: unleash
  url: https://github.com/Unleash/unleash
- anchor: flagsmith
  counts:
    declared: 0
    observed: 16
  evidence:
  - route: source code
    url: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
  - route: source code
    url: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations/lead_tracking
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    name: Dynatrace
    provider: dynatrace
    says: ships the Dynatrace SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    name: Grafana
    provider: grafana-com
    says: ships the Grafana SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Heap
    provider: heap
    says: ships the Heap SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: ships the HubSpot SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations/lead_tracking
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    credit: null
    layer: domain
    name: LaunchDarkly
    provider: launchdarkly
    says: ships the LaunchDarkly SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Pylon (usepylon.com)
    provider: pylon
    says: ships the Pylon (usepylon.com) SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: RudderStack
    provider: rudderstack
    says: ships the RudderStack SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
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
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
    tier: observed
  kind: open-source-saas
  name: Flagsmith
  page: /applications/feature-flags-experimentation/flagsmith/
  slug: flagsmith
  url: https://github.com/Flagsmith/flagsmith
- anchor: growthbook
  counts:
    declared: 0
    observed: 20
  evidence:
  - route: dependency manifest
    url: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
  - route: source code
    url: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Adobe Experience Platform Query Service
    provider: adobe
    says: ships the Adobe Experience Platform Query Service SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Amazon Athena
    provider: amazon-athena
    says: ships the Amazon Athena SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    name: Amazon CloudWatch
    provider: amazon-cloudwatch
    says: ships the Amazon CloudWatch SDK or integration code
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: ships the Amazon Redshift SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: ClickHouse
    provider: clickhouse
    says: ships the ClickHouse SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Databricks
    provider: databricks
    says: ships the Databricks SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: ships the Google BigQuery SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    name: Mistral
    provider: mistral
    says: ships the Mistral SDK or integration code
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: ships the Mixpanel SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Vertica
    provider: vertica
    says: ships the Vertica SDK or integration code
    source: https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
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
    name: xAI
    provider: xai
    says: ships the xAI SDK or integration code
    source: https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
    tier: observed
  kind: open-source-saas
  name: GrowthBook
  page: /applications/feature-flags-experimentation/growthbook/
  slug: growthbook
  url: https://github.com/growthbook/growthbook
- anchor: flipt
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/flipt-io/flipt/blob/main/go.mod
  - route: source code
    url: https://github.com/flipt-io/flipt/tree/main/internal/server/authn/method
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    credit: null
    layer: domain
    name: Amazon ECR
    provider: amazon-ecr
    says: ships the Amazon ECR SDK or integration code
    source: https://github.com/flipt-io/flipt/blob/main/go.mod
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
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/flipt-io/flipt/blob/main/go.mod
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
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/flipt-io/flipt/blob/main/go.mod
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
    source: https://github.com/flipt-io/flipt/blob/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/flipt-io/flipt/tree/main/internal/server/authn/method
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
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/flipt-io/flipt/blob/main/go.mod
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Twilio Segment
    provider: segment
    says: ships the Twilio Segment SDK or integration code
    source: https://github.com/flipt-io/flipt/blob/main/go.mod
    tier: observed
  kind: self-hosted
  name: Flipt
  page: /applications/feature-flags-experimentation/flipt/
  slug: flipt
  url: https://github.com/flipt-io/flipt
- anchor: configcat
  counts:
    declared: 18
    observed: 0
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
    layer: common
    name: Zoho Flow
    provider: zoho-flow
    says: lists Zoho Flow as an integration
    source: https://configcat.com/docs/integrations/overview/
    tier: declared
  kind: commercial
  name: ConfigCat
  page: /applications/feature-flags-experimentation/configcat/
  slug: configcat
  url: https://configcat.com/
- anchor: statsig
  counts:
    declared: 33
    observed: 0
  evidence:
  - route: integrations page
    url: https://docs.statsig.com/integrations/introduction
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Akamai
    provider: akamai
    says: lists Akamai as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Amazon Redshift
    provider: amazon-redshift
    says: lists Amazon Redshift as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amplitude
    provider: amplitude
    says: lists Amplitude as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Azure AI
    provider: microsoft-azure-openai
    says: lists Azure AI as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Census
    provider: getcensus
    says: lists Census as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Cloudflare
    provider: cloudflare
    says: lists Cloudflare as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: agent
    name: Cloudflare Workers AI
    provider: cloudflare
    says: lists Cloudflare Workers AI as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Fastly
    provider: fastly
    says: lists Fastly as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Fivetran
    provider: fivetran
    says: lists Fivetran as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
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
    says: lists GitHub as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
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
    says: lists GitLab as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Google BigQuery
    provider: google-bigquery
    says: lists Google BigQuery as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Heap
    provider: heap
    says: lists Heap as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Hightouch
    provider: hightouch
    says: lists Hightouch as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: domain
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: mParticle
    provider: mparticle
    says: lists mParticle as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
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
    says: lists OpenAI as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    credit: null
    layer: common
    name: PagerDuty
    provider: pagerduty
    says: lists PagerDuty as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Pulumi
    provider: pulumi
    says: lists Pulumi as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: RevenueCat
    provider: revenuecat
    says: lists RevenueCat as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: RudderStack
    provider: rudderstack
    says: lists RudderStack as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Serverless Framework
    provider: serverless
    says: lists Serverless Framework as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    credit: null
    layer: domain
    name: Snowflake
    provider: snowflake
    says: lists Snowflake as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Stitch Data
    provider: stitch-data
    says: lists Stitch Data as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    credit: null
    layer: domain
    name: Terraform
    provider: terraform
    says: lists Terraform as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Twilio Segment
    provider: segment
    says: lists Twilio Segment as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Vercel
    provider: vercel
    says: lists Vercel as an integration
    source: https://docs.statsig.com/integrations/introduction
    tier: declared
  kind: commercial
  name: Statsig
  page: /applications/feature-flags-experimentation/statsig/
  slug: statsig
  url: https://statsig.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: feature-flags-experimentation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Developer Tools
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Software Development - Feature Toggle
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---feature-toggle
- category: Developer Tools
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
name: Feature Flags & Experimentation
needs:
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  fit: exact
  layer: domain
  why: flag import/migration between flag platforms
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: domain
  why: flag exposure and experiment events sent to product analytics
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: CDP / reverse-ETL audiences and event pipes feeding targeting
- capability:
    attribution: Turbo EA
    id: BC-4280.40.30
    key: BC-4280.40.30
    name: Experiment Result Adjudication
    url: /capabilities/experimentation-programme-management/
    via_parent: Experimentation Programme Management
  fit: exact
  layer: domain
  why: warehouse-native experiment analysis (nearest; see candidate node)
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: release monitoring, flag-change annotations, metric triggers
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  fit: exact
  layer: common
  why: flag-change notifications to team chat
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: code references and stale-flag cleanup in source control
- capability:
    attribution: Turbo EA
    id: BC-4210.10
    key: continuous-integration-management
    name: Continuous Integration Management
    url: /capabilities/continuous-integration-management/
    via_parent: null
  fit: exact
  layer: domain
  why: code-reference scans and flag evaluation in CI
- capability:
    attribution: Turbo EA
    id: BC-4210.20.10
    key: BC-4210.20.10
    name: Environment Provisioning
    url: /capabilities/environment-management/
    via_parent: Environment Management
  fit: exact
  layer: domain
  why: IaC and deployment pipelines that manage flags (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: edge flag stores at the CDN (nearest; see candidate node)
- capability:
    attribution: Turbo EA
    id: BC-4270.30
    key: developer-portal-management
    name: Developer Portal Management
    url: /capabilities/developer-portal-management/
    via_parent: null
  fit: exact
  layer: domain
  why: flags surfaced in internal developer portals
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  fit: exact
  layer: common
  why: flags linked to issues
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: exact
  layer: common
  why: flags embedded in wiki pages
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  fit: exact
  layer: common
  why: incident triggers and change approvals
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support tools linked to flags
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: workforce SSO into the flag console
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: iPaaS automation of flag events
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: flag/experiment event streams to message buses
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: persistent flag stores in managed databases
- capability:
    attribution: API Evangelist extension
    id: AE-905
    key: AE-905
    name: IDEs & AI Coding Assistants
    url: /capabilities/engineering-productivity-management/
    via_parent: Engineering Productivity Management
  fit: exact
  layer: domain
  why: IDE plugins for flags
- capability:
    attribution: Turbo EA
    id: BC-130.50
    key: privacy-data-protection-management
    name: Privacy & Data Protection Management
    url: /capabilities/privacy-data-protection-management/
    via_parent: null
  fit: exact
  layer: common
  why: personal-information discovery
- capability:
    attribution: Turbo EA
    id: BC-3700
    key: content-origination-production-management
    name: Content Origination & Production Management
    url: /capabilities/content-origination-production-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: content/copy variants driven by flags (nearest)
- capability:
    attribution: Turbo EA
    id: BC-1040.40
    key: asset-information-management
    name: Asset Information Management
    url: /capabilities/asset-information-management/
    via_parent: null
  fit: nearest
  layer: common
  why: cloud asset inventory of flag resources (nearest)
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: SaaS sign-up lead tracking
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM features inside the flag platform (AI configs, experiment summaries)
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for flag state and exports
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: SaaS billing
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  fit: exact
  layer: domain
  why: OCI flag bundles in container registries
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social login to the console
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - ConfigCat
      - Flagsmith
      - LaunchDarkly
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 47.7
      apps:
      - ConfigCat
      - Flagsmith
      - GrowthBook
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 60.8
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: observed
      url: /providers/mixpanel/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - ConfigCat
      - GrowthBook
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-aware
      agent_readiness: 26.3
      apps:
      - Flagsmith
      - LaunchDarkly
      - Statsig
      band: developing
      in_catalog: true
      kin_score: 40.6
      mcp:
        status: unknown
      name: Heap
      slug: heap
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Autocapture
      - Digital Analytics
      - Product Analytics
      tier: observed
      url: /providers/heap/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Flipt
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp: &id003
        status: none
      name: Twilio Segment
      slug: segment
      sources:
      - https://github.com/flipt-io/flipt/blob/main/go.mod
      status: profiled
      tags: &id004
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 59.4
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 58.3
      mcp:
        status: unknown
      name: Sprig
      slug: sprig
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Product Research
      - Surveys
      - User Insights
      tier: declared
      url: /providers/sprig/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 57.0
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: declared
      url: /providers/pendoio/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 42.3
      mcp:
        source: https://github.com/snowplow/snowplow-cli
        status: verified
      name: Snowplow
      slug: snowplow
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics Platform
      - Behavioral Data
      - Data Collection
      - Data Engineering
      tier: declared
      url: /providers/snowplow/
    - agent_band: agent-ready
      agent_readiness: 30.0
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 37.4
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/fullstory/
  - capability:
      attribution: Turbo EA
      id: BC-4280.40.30
      key: BC-4280.40.30
      name: Experiment Result Adjudication
      url: /capabilities/experimentation-programme-management/
      via_parent: Experimentation Programme Management
    providers:
    - agent_band: agent-native
      agent_readiness: 44.9
      apps:
      - GrowthBook
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 82.3
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: observed
      url: /providers/snowflake/
    - agent_band: agent-native
      agent_readiness: 44.5
      apps:
      - GrowthBook
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
        status: verified
      name: Amazon Redshift
      slug: amazon-redshift
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Lake
      tier: observed
      url: /providers/amazon-redshift/
    - agent_band: agent-ready
      agent_readiness: 40.8
      apps:
      - GrowthBook
      - LaunchDarkly
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 57.1
      mcp:
        source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
        status: verified
      name: Google BigQuery
      slug: google-bigquery
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Big Data
      - Cloud
      - Data Warehouse
      tier: observed
      url: /providers/google-bigquery/
    - agent_band: agent-ready
      agent_readiness: 58.5
      apps:
      - GrowthBook
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 77.1
      mcp:
        source: https://github.com/ClickHouse/mcp-clickhouse
        status: verified
      name: ClickHouse
      slug: clickhouse
      sources:
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - ClickHouse
      - Cloud Database
      - Column-Oriented
      tier: observed
      url: /providers/clickhouse/
    - agent_band: agent-native
      agent_readiness: 65.5
      apps:
      - GrowthBook
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 58.7
      mcp:
        source: https://docs.databricks.com/aws/en/generative-ai/mcp/
        status: verified
      name: Databricks
      slug: databricks
      sources:
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cleanroom
      - Databricks
      tier: observed
      url: /providers/databricks/
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - GrowthBook
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Platform Query Service
      slug: adobe
      sources:
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      status: profiled
      tags:
      - Adobe
      - Analytics
      - E-Signature
      - Fortune 1000
      tier: observed
      url: /providers/adobe/
    - agent_band: agent-native
      agent_readiness: 44.8
      apps:
      - GrowthBook
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Athena
      slug: amazon-athena
      sources:
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      status: profiled
      tags:
      - Amazon Athena
      - Analytics
      - SQL
      - Serverless
      tier: observed
      url: /providers/amazon-athena/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - GrowthBook
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Vertica
      slug: vertica
      sources:
      - https://github.com/growthbook/growthbook/tree/main/packages/back-end/src/integrations
      status: profiled
      tags:
      - Analytics Database
      - Data Lakehouse
      - Data Warehouse
      - Database
      tier: observed
      url: /providers/vertica/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - ConfigCat
      - Flagsmith
      - Flipt
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id001
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags: &id002
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Flagsmith
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp:
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - ConfigCat
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: declared
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: declared
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-aware
      agent_readiness: 24.0
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 56.2
      mcp:
        status: unknown
      name: Gitar
      slug: gitar
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CI/CD
      - Code Review
      - Company
      - Developer Tools
      tier: declared
      url: /providers/gitar/
  - capability:
      attribution: API Evangelist extension
      id: AE-932
      key: AE-932
      name: Edge Functions & Edge Config Stores
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id005
        source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
        status: verified
      name: Cloudflare
      slug: cloudflare
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags: &id006
      - AI Gateway
      - API Gateway
      - Artificial Intelligence
      - CDN
      tier: declared
      url: /providers/cloudflare/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - LaunchDarkly
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/fastly/mcp
        status: verified
      name: Fastly
      slug: fastly
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CDN
      - Edge Cloud
      - Edge Compute
      - WebAssembly
      tier: declared
      url: /providers/fastly/
    - agent_band: agent-ready
      agent_readiness: 50.0
      apps:
      - LaunchDarkly
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        source: https://vercel.com/docs/mcp/vercel-mcp
        status: verified
      name: Vercel
      slug: vercel
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AI Gateway
      - Gateways
      - Observability
      - Webhook
      tier: declared
      url: /providers/vercel/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - LaunchDarkly
      - Statsig
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Akamai
      slug: akamai
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CDN
      - Cloud
      - Edge Computing
      - Networks
      tier: declared
      url: /providers/akamai/
    - agent_band: agent-ready
      agent_readiness: 58.9
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/netlify/netlify-mcp
        status: verified
      name: Netlify
      slug: netlify
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CDN
      - Cloud
      - Continuous Deployment
      - Developer Tools
      tier: declared
      url: /providers/netlify/
  - capability:
      attribution: Turbo EA
      id: BC-4210.20.10
      key: BC-4210.20.10
      name: Environment Provisioning
      url: /capabilities/environment-management/
      via_parent: Environment Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.7
      apps:
      - ConfigCat
      - LaunchDarkly
      - Statsig
      band: developing
      in_catalog: true
      kin_score: 42.5
      mcp:
        source: https://github.com/hashicorp/terraform-mcp-server
        status: verified
      name: Terraform
      slug: terraform
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Cloud Infrastructure
      - DevOps
      - Infrastructure as Code
      - Open Source
      tier: declared
      url: /providers/terraform/
    - agent_band: agent-ready
      agent_readiness: 31.6
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 65.3
      mcp:
        status: none
      name: Okteto
      slug: okteto
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Cloud-Native
      - Company
      - Developer Environments
      - Kubernetes
      tier: declared
      url: /providers/okteto/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 61.8
      mcp:
        status: unknown
      name: Release (releaseapp.io)
      slug: release
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Developer Tools
      - Ephemeral Environments
      - Platform Engineering
      tier: declared
      url: /providers/release/
    - agent_band: agent-aware
      agent_readiness: 26.9
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 48.9
      mcp:
        source: https://github.com/ansible/aap-mcp-server
        status: verified
      name: Ansible
      slug: ansible
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Ansible
      - Automation
      - Configuration Management
      - DevOps
      tier: declared
      url: /providers/ansible/
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 47.0
      mcp:
        status: none
      name: Crossplane
      slug: crossplane
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Apache 2.0
      - CNCF
      - COMPOSITION
      - Cloud-Native
      tier: declared
      url: /providers/crossplane/
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - Statsig
      band: developing
      in_catalog: true
      kin_score: 45.5
      mcp:
        source: https://registry.npmjs.org/@pulumi/mcp-server
        status: verified
      name: Pulumi
      slug: pulumi
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Automation
      - Cloud
      - DevOps
      - Infrastructure as Code
      tier: declared
      url: /providers/pulumi/
    - agent_band: human-only
      agent_readiness: 4.1
      apps:
      - Statsig
      band: thin
      in_catalog: true
      kin_score: 36.6
      mcp:
        source: https://www.serverless.com/framework/docs/guides/mcp
        status: verified
      name: Serverless Framework
      slug: serverless
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Company
      - Developer Tools
      - Infrastructure as Code
      - Serverless
      tier: declared
      url: /providers/serverless/
  - capability:
      attribution: Turbo EA
      id: BC-4210.10
      key: continuous-integration-management
      name: Continuous Integration Management
      url: /capabilities/continuous-integration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.3
      apps:
      - ConfigCat
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 73.5
      mcp:
        source: https://github.com/CircleCI-Public/mcp-server-circleci
        status: verified
      name: CircleCI
      slug: circleci
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CI/CD
      - Continuous Deployment
      - Continuous Integration
      - DevOps
      tier: declared
      url: /providers/circleci/
    - agent_band: agent-aware
      agent_readiness: 12.0
      apps:
      - ConfigCat
      - LaunchDarkly
      band: minimal
      in_catalog: true
      kin_score: 5.1
      mcp:
        source: https://github.com/bitrise-io/bitrise-mcp
        status: verified
      name: Bitrise
      slug: bitrise
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Continuous Integration
      - Developer Tools
      - Public APIs
      tier: declared
      url: /providers/bitrise/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub Actions
      slug: github
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/github/
  - capability:
      attribution: API Evangelist extension
      id: AE-905
      key: AE-905
      name: IDEs & AI Coding Assistants
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - ConfigCat
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 54.0
      mcp:
        source: https://github.com/JetBrains/mcp-server-plugin
        status: verified
      name: JetBrains IntelliJ
      slug: jetbrains
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CI/CD
      - Developer Tools
      - IDE
      - JetBrains
      tier: declared
      url: /providers/jetbrains/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - ConfigCat
      - LaunchDarkly
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: none
      name: VS Code
      slug: visual-studio-code
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Code Editor
      - Developer Tools
      - IDE
      - Open Source
      tier: declared
      url: /providers/visual-studio-code/
    - agent_band: agent-ready
      agent_readiness: 35.2
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 56.3
      mcp:
        source: https://docs.devin.ai/work-with-devin/devin-mcp
        status: verified
      name: Devin (Cognition)
      slug: cognition-labs
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Autonomous Coding
      - Software Engineering
      tier: declared
      url: /providers/cognition-labs/
  - capability:
      attribution: Turbo EA
      id: BC-4270.30
      key: developer-portal-management
      name: Developer Portal Management
      url: /capabilities/developer-portal-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 75.4
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Atlassian Compass
      slug: atlassian-compass
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Atlassian
      - Component Management
      - Developer Experience
      - Software Catalog
      tier: declared
      url: /providers/atlassian-compass/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://github.com/port-labs/port-mcp-server
        status: verified
      name: Port
      slug: port-io
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Internal Developer Portal
      - Platform Engineering
      - Self-Service Actions
      - Service Catalog
      tier: declared
      url: /providers/port-io/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: unknown
      name: Cortex
      slug: cortex-idp
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Developer Experience
      - Internal Developer Portal
      - Service Catalog
      - Software Catalog
      tier: declared
      url: /providers/cortex-idp/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 27.8
      mcp:
        status: unknown
      name: Roadie
      slug: roadie-io
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Backstage
      - Developer Experience
      - Internal Developer Portal
      - Software Catalog
      tier: declared
      url: /providers/roadie-io/
  - capability:
      attribution: Turbo EA
      id: BC-4210.50
      key: feature-flag-management
      name: Feature Flag Management
      url: /capabilities/feature-flag-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.7
      apps:
      - Flagsmith
      band: exemplar
      in_catalog: true
      kin_score: 84.5
      mcp:
        source: https://launchdarkly.com/docs/home/getting-started/mcp
        status: verified
      name: LaunchDarkly
      slug: launchdarkly
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Observability
      tier: observed
      url: /providers/launchdarkly/
    - agent_band: agent-ready
      agent_readiness: 59.5
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 75.7
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=statsig
        status: verified
      name: Statsig
      slug: statsig
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - A/B Testing
      - Experimentation
      - Feature Flags
      - Product Analytics
      tier: declared
      url: /providers/statsig/
    - agent_band: agent-ready
      agent_readiness: 33.4
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp:
        source: https://github.com/Unleash/unleash-mcp
        status: verified
      name: Unleash
      slug: unleash
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - A/B Testing
      - Feature Flags
      - Feature Management
      - Progressive Delivery
      tier: declared
      url: /providers/unleash/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: none
      name: Split (Harness FME)
      slug: split
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Experimentation
      - Feature Flags
      - Feature Management
      - Rollouts
      tier: declared
      url: /providers/split/
  - capability:
      attribution: Turbo EA
      id: BC-4210
      key: software-release-deployment-management
      name: Software Release & Deployment Management
      url: /capabilities/software-release-deployment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.6
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 50.8
      mcp:
        status: none
      name: ngrok
      slug: ngrok
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AI Gateway
      - API Gateway
      - Compute
      - Developer Tools
      tier: declared
      url: /providers/ngrok/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 41.0
      mcp:
        source: https://github.com/kosli-dev/mcp-server
        status: verified
      name: Kosli
      slug: kosli
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Compliance
      - Governance
      tier: declared
      url: /providers/kosli/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 30.1
      mcp:
        status: unknown
      name: Sleuth
      slug: sleuth
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - DORA
      - Deployment Tracking
      - DevOps
      - Engineering Metrics
      tier: declared
      url: /providers/sleuth/
    - agent_band: null
      agent_readiness: null
      apps:
      - LaunchDarkly
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Liquibase
      slug: liquibase
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-3700
      key: content-origination-production-management
      name: Content Origination & Production Management
      url: /capabilities/content-origination-production-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 52.8
      mcp:
        source: https://developer.dittowords.com/mcp-reference/overview
        status: verified
      name: Ditto (dittowords.com)
      slug: dittowords
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Content
      - Localization
      tier: declared
      url: /providers/dittowords/
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://github.com/contentful/contentful-mcp-server
        status: verified
      name: Contentful
      slug: contentful
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CMS
      - Content
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/contentful/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 41.0
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon DynamoDB
      slug: amazon-dynamodb
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - Document Store
      - Key-Value Store
      tier: declared
      url: /providers/amazon-dynamodb/
    - agent_band: agent-ready
      agent_readiness: 38.4
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 50.7
      mcp:
        source: https://docs.convex.dev/ai/convex-mcp-server
        status: verified
      name: Convex
      slug: convex
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Backend
      - Database
      - Functions
      - Real-Time
      tier: declared
      url: /providers/convex/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10.20
      key: AE-250.10.20
      name: Container Registries
      url: /capabilities/package-registries-distribution/
      via_parent: Package Registries & Distribution
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - Flipt
      band: exemplar
      in_catalog: true
      kin_score: 75.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon ECR
      slug: amazon-ecr
      sources:
      - https://github.com/flipt-io/flipt/blob/main/go.mod
      status: profiled
      tags:
      - Amazon Web Services
      - Container Images
      - Container Registry
      - Containers
      tier: observed
      url: /providers/amazon-ecr/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - ConfigCat
      - Flagsmith
      - LaunchDarkly
      - Statsig
      - Unleash
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Flagsmith
      - GrowthBook
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Flagsmith
      - LaunchDarkly
      - Unleash
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/Unleash/unleash/tree/main/src/lib/addons
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 43.8
      apps:
      - Flagsmith
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 85.6
      mcp:
        source: https://github.com/dynatrace-oss/dynatrace-mcp
        status: verified
      name: Dynatrace
      slug: dynatrace
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AI Operations
      - APM
      - Analytics
      - Application Performance Monitoring
      tier: observed
      url: /providers/dynatrace/
    - agent_band: agent-aware
      agent_readiness: 27.6
      apps:
      - Flagsmith
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        source: https://github.com/grafana/mcp-grafana
        status: verified
      name: Grafana
      slug: grafana-com
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Dashboards
      - Logs
      - Monitoring
      - Observability
      tier: observed
      url: /providers/grafana-com/
    - agent_band: agent-native
      agent_readiness: 43.4
      apps:
      - GrowthBook
      band: exemplar
      in_catalog: true
      kin_score: 77.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon CloudWatch
      slug: amazon-cloudwatch
      sources:
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
      status: profiled
      tags:
      - Amazon Web Services
      - CloudWatch
      - Monitoring
      - Observability
      tier: observed
      url: /providers/amazon-cloudwatch/
    - agent_band: agent-ready
      agent_readiness: 29.8
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 80.1
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS CloudTrail
      slug: amazon-cloudtrail
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Audit
      - CloudTrail
      - Compliance
      tier: declared
      url: /providers/amazon-cloudtrail/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elastic
      slug: elastic
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: declared
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 55.5
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 71.6
      mcp:
        source: https://docs.honeycomb.io/integrations/mcp/
        status: verified
      name: Honeycomb
      slug: honeycomb
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Data Management
      - Observability
      - Telemetry
      tier: declared
      url: /providers/honeycomb/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 69.2
      mcp:
        status: none
      name: SolarWinds AppOptics
      slug: solarwinds
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Application Monitoring
      - Database Monitoring
      - IP Address Management
      - Infrastructure
      tier: declared
      url: /providers/solarwinds/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        source: https://help.splunk.com/en/splunk-observability-cloud/splunk-ai-assistant/interact-with-your-observability-data-using-the-splunk-mcp-server
        status: verified
      name: SignalFx (Splunk Observability)
      slug: splunk-observability
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - APM
      - Monitoring
      - Observability
      - Telemetry
      tier: declared
      url: /providers/splunk-observability/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk
      slug: splunk
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: declared
      url: /providers/splunk/
    - agent_band: agent-native
      agent_readiness: 58.7
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        source: https://github.com/chronosphereio/chronosphere-mcp
        status: verified
      name: Chronosphere
      slug: chronosphere
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AIOps
      - Metrics
      - Monitoring
      - Observability
      tier: declared
      url: /providers/chronosphere/
    - agent_band: agent-aware
      agent_readiness: 27.1
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/mezmo/mezmo-mcp
        status: verified
      name: Mezmo (LogDNA)
      slug: mezmo
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Logs
      - Observability
      - Telemetry
      - Telemetry Pipeline
      tier: declared
      url: /providers/mezmo/
    - agent_band: agent-aware
      agent_readiness: 18.9
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 35.5
      mcp:
        status: none
      name: AppDynamics
      slug: appdynamics
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - APM
      - Application Performance Monitoring
      - Cisco
      - Cloud Observability
      tier: declared
      url: /providers/appdynamics/
    - agent_band: human-only
      agent_readiness: 3.9
      apps:
      - LaunchDarkly
      band: emerging
      in_catalog: true
      kin_score: 21.2
      mcp:
        source: https://last9.io/docs/mcp
        status: verified
      name: Last9
      slug: last9
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Company
      - DevOps
      - Monitoring
      - Observability
      tier: declared
      url: /providers/last9/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.7
      apps:
      - ConfigCat
      - Flagsmith
      - LaunchDarkly
      - Statsig
      band: developing
      in_catalog: true
      kin_score: 42.9
      mcp: *id003
      name: Twilio Segment
      slug: segment
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/segment/
    - agent_band: agent-ready
      agent_readiness: 56.9
      apps:
      - Flagsmith
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 79.1
      mcp:
        source: https://github.com/rudderlabs/rudderstack-mcp
        status: verified
      name: RudderStack
      slug: rudderstack
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CDP
      - Customer Data Platform
      - Data Pipeline
      - Open Source
      tier: observed
      url: /providers/rudderstack/
    - agent_band: agent-ready
      agent_readiness: 62.8
      apps:
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 66.9
      mcp:
        source: https://hightouch.com/docs/ai-integrations/mcp
        status: documented
      name: Hightouch
      slug: hightouch
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Audience Management
      - CDP
      - Data Activation
      - Reverse ETL
      tier: declared
      url: /providers/hightouch/
    - agent_band: agent-aware
      agent_readiness: 26.0
      apps:
      - LaunchDarkly
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        status: none
      name: Census
      slug: getcensus
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Census
      - Data Activation
      - Reverse ETL
      - Sync
      tier: declared
      url: /providers/getcensus/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - LaunchDarkly
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 59.5
      mcp:
        status: none
      name: mParticle
      slug: mparticle
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Analytics
      - CDP
      - Customer Data Platform
      - Identity Resolution
      tier: declared
      url: /providers/mparticle/
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 66.5
      mcp:
        source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
        status: documented
      name: Tealium
      slug: tealium
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AudienceStream
      - CDP
      - Customer Data Platform
      - Tag Management
      tier: declared
      url: /providers/tealium/
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Statsig
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
    - agent_band: agent-ready
      agent_readiness: 38.9
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 52.2
      mcp:
        status: none
      name: Zeotap
      slug: zeotap
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Customer Data Platform
      - Data Integration
      tier: declared
      url: /providers/zeotap/
    - agent_band: human-only
      agent_readiness: 3.8
      apps:
      - Statsig
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Stitch Data
      slug: stitch-data
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Cloud Data
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/stitch-data/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Statsig
      band: thin
      in_catalog: true
      kin_score: 34.2
      mcp:
        source: https://github.com/fivetran/fivetran-mcp
        status: verified
      name: Fivetran
      slug: fivetran
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Connectors
      - Data Integration
      - Data Pipeline
      - ETL
      tier: declared
      url: /providers/fivetran/
    - agent_band: agent-aware
      agent_readiness: 23.8
      apps:
      - Statsig
      band: thin
      in_catalog: true
      kin_score: 27.4
      mcp:
        source: https://www.revenuecat.com/docs/tools/mcp
        status: verified
      name: RevenueCat
      slug: revenuecat
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Billing
      - In-App Purchases
      - Mobile
      - Subscription
      tier: declared
      url: /providers/revenuecat/
    - agent_band: null
      agent_readiness: null
      apps:
      - LaunchDarkly
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Fulcrum (getfulcrum.io)
      slug: getfulcrum
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
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
      - ConfigCat
      - Flagsmith
      - LaunchDarkly
      - Statsig
      - Unleash
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - LaunchDarkly
      - Unleash
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://github.com/Unleash/unleash/tree/main/src/lib/addons
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
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
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: declared
      url: /providers/mattermost/
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
      - ConfigCat
      - LaunchDarkly
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - ConfigCat
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 50.3
      apps:
      - ConfigCat
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        source: https://github.com/mondaycom/mcp
        status: verified
      name: monday.com
      slug: monday-com
      sources:
      - https://configcat.com/docs/integrations/overview/
      status: profiled
      tags:
      - Automation
      - CRM
      - GraphQL
      - Work Management
      tier: declared
      url: /providers/monday-com/
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
      - Flipt
      - GrowthBook
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/flipt-io/flipt/blob/main/go.mod
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
      - Flipt
      - GrowthBook
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/flipt-io/flipt/blob/main/go.mod
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
      - Flipt
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/flipt-io/flipt/blob/main/go.mod
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - LaunchDarkly
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: declared
      url: /providers/onelogin/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - ConfigCat
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://configcat.com/docs/integrations/overview/
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 60.3
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 89.5
      mcp:
        source: https://docs.tray.ai/
        status: documented
      name: Tray.ai
      slug: tray-ai
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - AI Agents
      - Automation
      - Integration
      - iPaaS
      tier: declared
      url: /providers/tray-ai/
    - agent_band: null
      agent_readiness: null
      apps:
      - ConfigCat
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Zoho Flow
      slug: zoho-flow
      sources:
      - https://configcat.com/docs/integrations/overview/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4220.30
      key: incident-response-management
      name: Incident Response Management
      url: /capabilities/incident-response-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - LaunchDarkly
      - Statsig
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        source: https://github.com/PagerDuty/pagerduty-mcp-server
        status: verified
      name: PagerDuty
      slug: pagerduty
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Alerting
      - DevOps
      - Incident Management
      - On-Call Management
      tier: declared
      url: /providers/pagerduty/
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.6
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        status: none
      name: Amazon Kinesis
      slug: kinesis
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Apache Flink
      - Big Data
      tier: declared
      url: /providers/kinesis/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 68.4
      mcp:
        source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-event-hubs
        status: verified
      name: Azure Event Hubs
      slug: microsoft-azure-event-hubs
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Big Data
      - Event Streaming
      - IoT
      - Message Ingestion
      tier: declared
      url: /providers/microsoft-azure-event-hubs/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 64.1
      mcp:
        source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
        status: verified
      name: Google Cloud Pub/Sub
      slug: google-cloud-pubsub
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Event-Driven
      - Google Cloud
      - Messaging
      - Pub/Sub
      tier: declared
      url: /providers/google-cloud-pubsub/
  - capability:
      attribution: Turbo EA
      id: BC-1040.40
      key: asset-information-management
      name: Asset Information Management
      url: /capabilities/asset-information-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - LaunchDarkly
      band: developing
      in_catalog: true
      kin_score: 39.7
      mcp:
        source: https://github.com/cloudquery/mcp-releases
        status: verified
      name: CloudQuery
      slug: cloudquery
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CSPM
      - Cloud Asset Inventory
      - Cloud Governance
      - Cloud Infrastructure
      tier: declared
      url: /providers/cloudquery/
    - agent_band: null
      agent_readiness: null
      apps:
      - LaunchDarkly
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Resmo
      slug: resmo
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Flagsmith
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: unknown
      name: Pylon (usepylon.com)
      slug: pylon
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations
      status: profiled
      tags:
      - Customer Operations
      - Customer Service
      - Knowledge Base
      - Ticketing
      tier: observed
      url: /providers/pylon/
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
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
      - Flagsmith
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://github.com/Flagsmith/flagsmith/tree/main/api/integrations/lead_tracking
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: observed
      url: /providers/hubspot/
  - capability:
      attribution: Turbo EA
      id: BC-830.30
      key: knowledge-sharing-collaboration-management
      name: Knowledge Sharing & Collaboration Management
      url: /capabilities/knowledge-sharing-collaboration-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 55.8
      apps:
      - LaunchDarkly
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Confluence
      slug: confluence
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Collaboration
      - Content Management
      - Documentation
      - Knowledge Base
      tier: declared
      url: /providers/confluence/
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
      - GrowthBook
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-130.50
      key: privacy-data-protection-management
      name: Privacy & Data Protection Management
      url: /capabilities/privacy-data-protection-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - LaunchDarkly
      band: strong
      in_catalog: true
      kin_score: 54.3
      mcp:
        status: none
      name: Osano
      slug: osano
      sources:
      - https://github.com/launchdarkly/integration-framework/tree/main/integrations
      status: profiled
      tags:
      - Company
      - Compliance
      - Consent Management
      - Privacy
      tier: declared
      url: /providers/osano/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Flipt
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id001
      name: GitHub
      slug: github
      sources:
      - https://github.com/flipt-io/flipt/tree/main/internal/server/authn/method
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/github/
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
      - GrowthBook
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://docs.statsig.com/integrations/introduction
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
      - GrowthBook
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - GrowthBook
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
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
      - GrowthBook
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral
      slug: mistral
      sources:
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - GrowthBook
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        status: none
      name: xAI
      slug: xai
      sources:
      - https://github.com/growthbook/growthbook/blob/main/packages/back-end/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Grok
      - LLM
      tier: observed
      url: /providers/xai/
    - agent_band: agent-native
      agent_readiness: 69.4
      apps:
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id005
      name: Cloudflare Workers AI
      slug: cloudflare
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/cloudflare/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Statsig
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure AI
      slug: microsoft-azure-openai
      sources:
      - https://docs.statsig.com/integrations/introduction
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: declared
      url: /providers/microsoft-azure-openai/
  layer: agent
summary:
  coverage_pct: 96.6
  declared_only: 82
  distinct_providers: 119
  in_catalog: 115
  mcp:
    documented: 4
    none: 25
    unchecked: 4
    verified: 78
  mcp_verified: 78
  mean_kin_score: 60.4
  observed: 37
  queued: 4
  reference_apps: 7
title: 'Feature Flags & Experimentation: application blueprint'
---
