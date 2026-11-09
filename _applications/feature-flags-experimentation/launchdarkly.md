---
app: LaunchDarkly
app_slug: launchdarkly
app_url: https://launchdarkly.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-3700
  key: content-origination-production-management
  layer: domain
  name: Content Origination & Production Management
  providers:
  - Contentful
  - Ditto (dittowords.com)
  url: /capabilities/content-origination-production-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - Bitrise
  - CircleCI
  - GitHub Actions
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.30
  key: developer-portal-management
  layer: domain
  name: Developer Portal Management
  providers:
  - Atlassian Compass
  - Cortex
  - Port
  - Roadie
  url: /capabilities/developer-portal-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-932
  key: AE-932
  layer: domain
  name: Edge Functions & Edge Config Stores
  providers:
  - Akamai
  - Cloudflare
  - Fastly
  - Netlify
  - Vercel
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.20.10
  key: BC-4210.20.10
  layer: domain
  name: Environment Provisioning
  providers:
  - Ansible
  - Crossplane
  - Okteto
  - Release (releaseapp.io)
  - Terraform
  url: /capabilities/environment-management/
  via_parent: Environment Management
- attribution: Turbo EA
  id: BC-4280.40.30
  key: BC-4280.40.30
  layer: domain
  name: Experiment Result Adjudication
  providers:
  - Amazon Redshift
  - ClickHouse
  - Databricks
  - Google BigQuery
  - Snowflake
  url: /capabilities/experimentation-programme-management/
  via_parent: Experimentation Programme Management
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: domain
  name: Feature Flag Management
  providers:
  - Split (Harness FME)
  - Statsig
  - Unleash
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-905
  key: AE-905
  layer: domain
  name: IDEs & AI Coding Assistants
  providers:
  - Devin (Cognition)
  - JetBrains IntelliJ
  - VS Code
  url: /capabilities/engineering-productivity-management/
  via_parent: Engineering Productivity Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: domain
  name: Managed Operational Databases
  providers:
  - Amazon DynamoDB
  - Convex
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4280
  key: product-telemetry-experimentation-management
  layer: domain
  name: Product Telemetry & Experimentation Management
  providers:
  - Amplitude
  - FullStory
  - Heap
  - Pendo
  - Snowplow
  - Sprig
  url: /capabilities/product-telemetry-experimentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Azure DevOps
  - Bitbucket
  - Gitar
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210
  key: software-release-deployment-management
  layer: domain
  name: Software Release & Deployment Management
  providers:
  - Kosli
  - Liquibase
  - ngrok
  - Sleuth
  url: /capabilities/software-release-deployment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1040.40
  key: asset-information-management
  layer: common
  name: Asset Information Management
  providers:
  - CloudQuery
  - Resmo
  url: /capabilities/asset-information-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-420.10
  key: customer-data-management
  layer: common
  name: Customer Data Management
  providers:
  - Census
  - Fulcrum (getfulcrum.io)
  - Hightouch
  - mParticle
  - RudderStack
  - Tealium
  - Twilio Segment
  - Zeotap
  url: /capabilities/customer-data-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Zendesk
  url: /capabilities/customer-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - PagerDuty
  - ServiceNow
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon Kinesis
  - Azure Event Hubs
  - Google Cloud Pub/Sub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Mattermost
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Confluence
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - AppDynamics
  - AWS CloudTrail
  - Chronosphere
  - Datadog
  - Dynatrace
  - Elastic
  - Grafana
  - Honeycomb
  - Last9
  - Mezmo (LogDNA)
  - New Relic
  - Sentry
  - SignalFx (Splunk Observability)
  - SolarWinds AppOptics
  - Splunk
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-130.50
  key: privacy-data-protection-management
  layer: common
  name: Privacy & Data Protection Management
  providers:
  - Osano
  url: /capabilities/privacy-data-protection-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira
  - Trello
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Google Workspace
  - Microsoft Entra ID
  - Okta
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Tray.ai
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: feature-flags-experimentation
  name: Feature Flags & Experimentation
  url: /applications/feature-flags-experimentation/
counts:
  declared: 91
  observed: 0
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id002
      status: none
    slug: akamai
    status: profiled
    tags: &id003
    - CDN
    - Cloud
    - Edge Computing
    - Networks
    url: /providers/akamai/
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
  facts:
    agent_band: agent-native
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 80.9
    mcp: &id004
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-dynamodb
    status: profiled
    tags: &id005
    - Amazon Web Services
    - Database
    - Document Store
    - Key-Value Store
    url: /providers/amazon-dynamodb/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.4
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id006
      status: none
    slug: kinesis
    status: profiled
    tags: &id007
    - Amazon Web Services
    - Analytics
    - Apache Flink
    - Big Data
    url: /providers/kinesis/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 63.6
    mcp: &id008
      source: https://github.com/awslabs/mcp/tree/main/src/redshift-mcp-server
      status: verified
    slug: amazon-redshift
    status: profiled
    tags: &id009
    - Analytics
    - Big Data
    - Cloud
    - Data Lake
    url: /providers/amazon-redshift/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id010
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id011
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.9
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id012
      source: https://github.com/ansible/aap-mcp-server
      status: verified
    slug: ansible
    status: profiled
    tags: &id013
    - Ansible
    - Automation
    - Configuration Management
    - DevOps
    url: /providers/ansible/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id014
      status: none
    slug: appdynamics
    status: profiled
    tags: &id015
    - APM
    - Application Performance Monitoring
    - Cisco
    - Cloud Observability
    url: /providers/appdynamics/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.1
    band: exemplar
    in_catalog: true
    kin_score: 75.8
    mcp: &id016
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: atlassian-compass
    status: profiled
    tags: &id017
    - Atlassian
    - Component Management
    - Developer Experience
    - Software Catalog
    url: /providers/atlassian-compass/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id018
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudtrail
    status: profiled
    tags: &id019
    - Amazon Web Services
    - Audit
    - CloudTrail
    - Compliance
    url: /providers/amazon-cloudtrail/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id020
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id021
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: strong
    in_catalog: true
    kin_score: 64.7
    mcp: &id022
      source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-event-hubs
      status: verified
    slug: microsoft-azure-event-hubs
    status: profiled
    tags: &id023
    - Big Data
    - Event Streaming
    - IoT
    - Message Ingestion
    url: /providers/microsoft-azure-event-hubs/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 36.0
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id024
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id025
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.2
    band: minimal
    in_catalog: true
    kin_score: 6.0
    mcp: &id026
      source: https://github.com/bitrise-io/bitrise-mcp
      status: verified
    slug: bitrise
    status: profiled
    tags: &id027
    - Continuous Integration
    - Developer Tools
    - Public APIs
    url: /providers/bitrise/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id028
      status: none
    slug: getcensus
    status: profiled
    tags: &id029
    - Census
    - Data Activation
    - Reverse ETL
    - Sync
    url: /providers/getcensus/
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
  facts:
    agent_band: agent-native
    agent_readiness: 55.4
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id030
      source: https://github.com/chronosphereio/chronosphere-mcp
      status: verified
    slug: chronosphere
    status: profiled
    tags: &id031
    - AIOps
    - Metrics
    - Monitoring
    - Observability
    url: /providers/chronosphere/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.1
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id032
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id033
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 76.9
    mcp: &id034
      source: https://github.com/ClickHouse/mcp-clickhouse
      status: verified
    slug: clickhouse
    status: profiled
    tags: &id035
    - Analytics
    - ClickHouse
    - Cloud Database
    - Column-Oriented
    url: /providers/clickhouse/
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
  facts:
    agent_band: agent-native
    agent_readiness: 69.6
    band: exemplar
    in_catalog: true
    kin_score: 82.8
    mcp: &id036
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id037
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 40.0
    mcp: &id038
      source: https://github.com/cloudquery/mcp-releases
      status: verified
    slug: cloudquery
    status: profiled
    tags: &id039
    - CSPM
    - Cloud Asset Inventory
    - Cloud Governance
    - Cloud Infrastructure
    url: /providers/cloudquery/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id040
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: confluence
    status: profiled
    tags: &id041
    - Collaboration
    - Content Management
    - Documentation
    - Knowledge Base
    url: /providers/confluence/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.5
    band: developing
    in_catalog: true
    kin_score: 44.3
    mcp: &id042
      source: https://github.com/contentful/contentful-mcp-server
      status: verified
    slug: contentful
    status: profiled
    tags: &id043
    - CMS
    - Content
    - Content Management
    - Headless CMS
    url: /providers/contentful/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.8
    band: developing
    in_catalog: true
    kin_score: 51.5
    mcp: &id044
      source: https://docs.convex.dev/ai/convex-mcp-server
      status: verified
    slug: convex
    status: profiled
    tags: &id045
    - Backend
    - Database
    - Functions
    - Real-Time
    url: /providers/convex/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 34.1
    mcp: &id046
      status: unknown
    slug: cortex-idp
    status: profiled
    tags: &id047
    - Developer Experience
    - Internal Developer Portal
    - Service Catalog
    - Software Catalog
    url: /providers/cortex-idp/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 45.8
    mcp: &id048
      status: none
    slug: crossplane
    status: profiled
    tags: &id049
    - Apache 2.0
    - CNCF
    - COMPOSITION
    - Cloud-Native
    url: /providers/crossplane/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id050
      source: https://docs.databricks.com/aws/en/generative-ai/mcp/
      status: verified
    slug: databricks
    status: profiled
    tags: &id051
    - Analytics
    - Artificial Intelligence
    - Cleanroom
    - Databricks
    url: /providers/databricks/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
    mcp: &id052
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id053
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id054
      source: https://docs.devin.ai/work-with-devin/devin-mcp
      status: verified
    slug: cognition-labs
    status: profiled
    tags: &id055
    - AI Agents
    - Artificial Intelligence
    - Autonomous Coding
    - Software Engineering
    url: /providers/cognition-labs/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 42.2
    band: developing
    in_catalog: true
    kin_score: 46.6
    mcp: &id056
      source: https://developer.dittowords.com/mcp-reference/overview
      status: verified
    slug: dittowords
    status: profiled
    tags: &id057
    - Artificial Intelligence
    - Company
    - Content
    - Localization
    url: /providers/dittowords/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.7
    band: exemplar
    in_catalog: true
    kin_score: 84.1
    mcp: &id058
      source: https://github.com/dynatrace-oss/dynatrace-mcp
      status: verified
    slug: dynatrace
    status: profiled
    tags: &id059
    - AI Operations
    - APM
    - Analytics
    - Application Performance Monitoring
    url: /providers/dynatrace/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id060
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id061
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: strong
    in_catalog: true
    kin_score: 65.3
    mcp: &id062
      source: https://github.com/fastly/mcp
      status: verified
    slug: fastly
    status: profiled
    tags: &id063
    - CDN
    - Edge Cloud
    - Edge Compute
    - WebAssembly
    url: /providers/fastly/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id064
      status: unchecked
    slug: getfulcrum
    status: queued for profiling
    tags: &id065 []
    url: null
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: thin
    in_catalog: true
    kin_score: 37.1
    mcp: &id066
      source: https://developer.fullstory.com/mcp/introduction/
      status: documented
    slug: fullstory
    status: profiled
    tags: &id067
    - Behavioral Analytics
    - Digital Experience
    - Product Analytics
    - Session Replay
    url: /providers/fullstory/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id068
      status: unknown
    slug: gitar
    status: profiled
    tags: &id069
    - CI/CD
    - Code Review
    - Company
    - Developer Tools
    url: /providers/gitar/
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
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id070
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id071
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts: *id001
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
  facts:
    agent_band: agent-native
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 79.6
    mcp: &id072
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id073
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id074
      source: https://cloud.google.com/bigquery/docs/use-bigquery-mcp
      status: verified
    slug: google-bigquery
    status: profiled
    tags: &id075
    - Analytics
    - Big Data
    - Cloud
    - Data Warehouse
    url: /providers/google-bigquery/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.6
    band: thin
    in_catalog: true
    kin_score: 38.7
    mcp: &id076
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id077
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id078
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id079
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 60.6
    mcp: &id080
      source: https://github.com/grafana/mcp-grafana
      status: verified
    slug: grafana-com
    status: profiled
    tags: &id081
    - Dashboards
    - Logs
    - Monitoring
    - Observability
    url: /providers/grafana-com/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.9
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id082
      status: unknown
    slug: heap
    status: profiled
    tags: &id083
    - Analytics
    - Autocapture
    - Digital Analytics
    - Product Analytics
    url: /providers/heap/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 63.8
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id084
      source: https://hightouch.com/docs/ai-integrations/mcp
      status: documented
    slug: hightouch
    status: profiled
    tags: &id085
    - Audience Management
    - CDP
    - Data Activation
    - Reverse ETL
    url: /providers/hightouch/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 54.3
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id086
      source: https://docs.honeycomb.io/integrations/mcp/
      status: verified
    slug: honeycomb
    status: profiled
    tags: &id087
    - Analytics
    - Data Management
    - Observability
    - Telemetry
    url: /providers/honeycomb/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 48.4
    mcp: &id088
      source: https://github.com/JetBrains/mcp-server-plugin
      status: verified
    slug: jetbrains
    status: profiled
    tags: &id089
    - CI/CD
    - Developer Tools
    - IDE
    - JetBrains
    url: /providers/jetbrains/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id090
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id091
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id092
      source: https://github.com/kosli-dev/mcp-server
      status: verified
    slug: kosli
    status: profiled
    tags: &id093
    - Artificial Intelligence
    - Company
    - Compliance
    - Governance
    url: /providers/kosli/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id094
      source: https://last9.io/docs/mcp
      status: verified
    slug: last9
    status: profiled
    tags: &id095
    - Company
    - DevOps
    - Monitoring
    - Observability
    url: /providers/last9/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id096
      status: unchecked
    slug: liquibase
    status: queued for profiling
    tags: &id097 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.7
    band: thin
    in_catalog: true
    kin_score: 37.2
    mcp: &id098
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id099
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id100
      source: https://github.com/mezmo/mezmo-mcp
      status: verified
    slug: mezmo
    status: profiled
    tags: &id101
    - Logs
    - Observability
    - Telemetry
    - Telemetry Pipeline
    url: /providers/mezmo/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id102
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id103
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id104
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id105
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.7
    band: strong
    in_catalog: true
    kin_score: 58.7
    mcp: &id106
      status: none
    slug: mparticle
    status: profiled
    tags: &id107
    - Analytics
    - CDP
    - Customer Data Platform
    - Identity Resolution
    url: /providers/mparticle/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.8
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id108
      source: https://github.com/netlify/netlify-mcp
      status: verified
    slug: netlify
    status: profiled
    tags: &id109
    - CDN
    - Cloud
    - Continuous Deployment
    - Developer Tools
    url: /providers/netlify/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.7
    band: exemplar
    in_catalog: true
    kin_score: 76.5
    mcp: &id110
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id111
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.0
    band: developing
    in_catalog: true
    kin_score: 52.5
    mcp: &id112
      status: none
    slug: ngrok
    status: profiled
    tags: &id113
    - AI Gateway
    - API Gateway
    - Compute
    - Developer Tools
    url: /providers/ngrok/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id114
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id115
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 32.4
    band: strong
    in_catalog: true
    kin_score: 54.4
    mcp: &id116
      status: none
    slug: okteto
    status: profiled
    tags: &id117
    - Cloud-Native
    - Company
    - Developer Environments
    - Kubernetes
    url: /providers/okteto/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id118
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id119
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id120
      status: none
    slug: osano
    status: profiled
    tags: &id121
    - Company
    - Compliance
    - Consent Management
    - Privacy
    url: /providers/osano/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.9
    band: developing
    in_catalog: true
    kin_score: 51.2
    mcp: &id122
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id123
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.4
    band: strong
    in_catalog: true
    kin_score: 56.4
    mcp: &id124
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id125
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 22.7
    band: developing
    in_catalog: true
    kin_score: 44.0
    mcp: &id126
      source: https://github.com/port-labs/port-mcp-server
      status: verified
    slug: port-io
    status: profiled
    tags: &id127
    - Internal Developer Portal
    - Platform Engineering
    - Self-Service Actions
    - Service Catalog
    url: /providers/port-io/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id128
      status: unknown
    slug: release
    status: profiled
    tags: &id129
    - Company
    - Developer Tools
    - Ephemeral Environments
    - Platform Engineering
    url: /providers/release/
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
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id130
      status: unchecked
    slug: resmo
    status: queued for profiling
    tags: &id131 []
    url: null
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 27.5
    mcp: &id132
      status: unknown
    slug: roadie-io
    status: profiled
    tags: &id133
    - Backstage
    - Developer Experience
    - Internal Developer Portal
    - Software Catalog
    url: /providers/roadie-io/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 58.1
    band: exemplar
    in_catalog: true
    kin_score: 78.5
    mcp: &id134
      source: https://github.com/rudderlabs/rudderstack-mcp
      status: verified
    slug: rudderstack
    status: profiled
    tags: &id135
    - CDP
    - Customer Data Platform
    - Data Pipeline
    - Open Source
    url: /providers/rudderstack/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id136
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id137
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.2
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id138
      status: none
    slug: servicenow
    status: profiled
    tags: &id139
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 69.5
    mcp: &id140
      source: https://help.splunk.com/en/splunk-observability-cloud/splunk-ai-assistant/interact-with-your-observability-data-using-the-splunk-mcp-server
      status: verified
    slug: splunk-observability
    status: profiled
    tags: &id141
    - APM
    - Monitoring
    - Observability
    - Telemetry
    url: /providers/splunk-observability/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id142
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id143
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id144
      status: unknown
    slug: sleuth
    status: profiled
    tags: &id145
    - DORA
    - Deployment Tracking
    - DevOps
    - Engineering Metrics
    url: /providers/sleuth/
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
  facts:
    agent_band: agent-native
    agent_readiness: 45.8
    band: exemplar
    in_catalog: true
    kin_score: 81.1
    mcp: &id146
      source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
      status: verified
    slug: snowflake
    status: profiled
    tags: &id147
    - Data
    - Data Lakehouse
    - Data Warehouse
    - Snowflake
    url: /providers/snowflake/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id148
      source: https://github.com/snowplow/snowplow-cli
      status: verified
    slug: snowplow
    status: profiled
    tags: &id149
    - Analytics Platform
    - Behavioral Data
    - Data Collection
    - Data Engineering
    url: /providers/snowplow/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id150
      status: none
    slug: solarwinds
    status: profiled
    tags: &id151
    - Application Monitoring
    - Database Monitoring
    - IP Address Management
    - Infrastructure
    url: /providers/solarwinds/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id152
      status: none
    slug: split
    status: profiled
    tags: &id153
    - Experimentation
    - Feature Flags
    - Feature Management
    - Rollouts
    url: /providers/split/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id154
      status: none
    slug: splunk
    status: profiled
    tags: &id155
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.6
    band: strong
    in_catalog: true
    kin_score: 57.8
    mcp: &id156
      status: unknown
    slug: sprig
    status: profiled
    tags: &id157
    - Company
    - Product Research
    - Surveys
    - User Insights
    url: /providers/sprig/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.6
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id158
      source: https://registry.modelcontextprotocol.io/v0/servers?search=statsig
      status: verified
    slug: statsig
    status: profiled
    tags: &id159
    - A/B Testing
    - Experimentation
    - Feature Flags
    - Product Analytics
    url: /providers/statsig/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id160
      source: https://docs.tealium.com/server-side/config-mcp/about-config-mcp/
      status: documented
    slug: tealium
    status: profiled
    tags: &id161
    - AudienceStream
    - CDP
    - Customer Data Platform
    - Tag Management
    url: /providers/tealium/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: developing
    in_catalog: true
    kin_score: 43.6
    mcp: &id162
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id163
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 61.6
    band: exemplar
    in_catalog: true
    kin_score: 89.6
    mcp: &id164
      source: https://docs.tray.ai/
      status: documented
    slug: tray-ai
    status: profiled
    tags: &id165
    - AI Agents
    - Automation
    - Integration
    - iPaaS
    url: /providers/tray-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 75.6
    mcp: &id166
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id167
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id168
      status: none
    slug: segment
    status: profiled
    tags: &id169
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: developing
    in_catalog: true
    kin_score: 45.4
    mcp: &id170
      source: https://github.com/Unleash/unleash-mcp
      status: verified
    slug: unleash
    status: profiled
    tags: &id171
    - A/B Testing
    - Feature Flags
    - Feature Management
    - Progressive Delivery
    url: /providers/unleash/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.2
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id172
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id173
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id174
      status: none
    slug: visual-studio-code
    status: profiled
    tags: &id175
    - Code Editor
    - Developer Tools
    - IDE
    - Open Source
    url: /providers/visual-studio-code/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id176
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id177
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.8
    mcp: &id178
      status: none
    slug: zendesk
    status: profiled
    tags: &id179
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 43.4
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id180
      status: none
    slug: zeotap
    status: profiled
    tags: &id181
    - Artificial Intelligence
    - Company
    - Customer Data Platform
    - Data Integration
    url: /providers/zeotap/
  layer: common
  name: Zeotap
  provider: zeotap
  says: lists Zeotap as an integration
  source: https://github.com/launchdarkly/integration-framework/tree/main/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/feature-flags-experimentation/launchdarkly/
providers:
- agent_band: agent-ready
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id002
  name: Akamai
  slug: akamai
  status: profiled
  tags: *id003
  url: /providers/akamai/
- agent_band: agent-native
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 80.9
  mcp: *id004
  name: Amazon DynamoDB
  slug: amazon-dynamodb
  status: profiled
  tags: *id005
  url: /providers/amazon-dynamodb/
- agent_band: agent-ready
  agent_readiness: 29.4
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id006
  name: Amazon Kinesis
  slug: kinesis
  status: profiled
  tags: *id007
  url: /providers/kinesis/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 63.6
  mcp: *id008
  name: Amazon Redshift
  slug: amazon-redshift
  status: profiled
  tags: *id009
  url: /providers/amazon-redshift/
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id010
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id011
  url: /providers/amplitude/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id012
  name: Ansible
  slug: ansible
  status: profiled
  tags: *id013
  url: /providers/ansible/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id014
  name: AppDynamics
  slug: appdynamics
  status: profiled
  tags: *id015
  url: /providers/appdynamics/
- agent_band: agent-ready
  agent_readiness: 49.1
  band: exemplar
  in_catalog: true
  kin_score: 75.8
  mcp: *id016
  name: Atlassian Compass
  slug: atlassian-compass
  status: profiled
  tags: *id017
  url: /providers/atlassian-compass/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id018
  name: AWS CloudTrail
  slug: amazon-cloudtrail
  status: profiled
  tags: *id019
  url: /providers/amazon-cloudtrail/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id020
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id021
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: strong
  in_catalog: true
  kin_score: 64.7
  mcp: *id022
  name: Azure Event Hubs
  slug: microsoft-azure-event-hubs
  status: profiled
  tags: *id023
  url: /providers/microsoft-azure-event-hubs/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id024
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id025
  url: /providers/bitbucket/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: minimal
  in_catalog: true
  kin_score: 6.0
  mcp: *id026
  name: Bitrise
  slug: bitrise
  status: profiled
  tags: *id027
  url: /providers/bitrise/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id028
  name: Census
  slug: getcensus
  status: profiled
  tags: *id029
  url: /providers/getcensus/
- agent_band: agent-native
  agent_readiness: 55.4
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id030
  name: Chronosphere
  slug: chronosphere
  status: profiled
  tags: *id031
  url: /providers/chronosphere/
- agent_band: agent-ready
  agent_readiness: 56.1
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id032
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id033
  url: /providers/circleci/
- agent_band: agent-ready
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 76.9
  mcp: *id034
  name: ClickHouse
  slug: clickhouse
  status: profiled
  tags: *id035
  url: /providers/clickhouse/
- agent_band: agent-native
  agent_readiness: 69.6
  band: exemplar
  in_catalog: true
  kin_score: 82.8
  mcp: *id036
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id037
  url: /providers/cloudflare/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 40.0
  mcp: *id038
  name: CloudQuery
  slug: cloudquery
  status: profiled
  tags: *id039
  url: /providers/cloudquery/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id040
  name: Confluence
  slug: confluence
  status: profiled
  tags: *id041
  url: /providers/confluence/
- agent_band: agent-ready
  agent_readiness: 56.5
  band: developing
  in_catalog: true
  kin_score: 44.3
  mcp: *id042
  name: Contentful
  slug: contentful
  status: profiled
  tags: *id043
  url: /providers/contentful/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: developing
  in_catalog: true
  kin_score: 51.5
  mcp: *id044
  name: Convex
  slug: convex
  status: profiled
  tags: *id045
  url: /providers/convex/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 34.1
  mcp: *id046
  name: Cortex
  slug: cortex-idp
  status: profiled
  tags: *id047
  url: /providers/cortex-idp/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 45.8
  mcp: *id048
  name: Crossplane
  slug: crossplane
  status: profiled
  tags: *id049
  url: /providers/crossplane/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id050
  name: Databricks
  slug: databricks
  status: profiled
  tags: *id051
  url: /providers/databricks/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id052
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id053
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id054
  name: Devin (Cognition)
  slug: cognition-labs
  status: profiled
  tags: *id055
  url: /providers/cognition-labs/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: developing
  in_catalog: true
  kin_score: 46.6
  mcp: *id056
  name: Ditto (dittowords.com)
  slug: dittowords
  status: profiled
  tags: *id057
  url: /providers/dittowords/
- agent_band: agent-ready
  agent_readiness: 44.7
  band: exemplar
  in_catalog: true
  kin_score: 84.1
  mcp: *id058
  name: Dynatrace
  slug: dynatrace
  status: profiled
  tags: *id059
  url: /providers/dynatrace/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id060
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id061
  url: /providers/elastic/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: strong
  in_catalog: true
  kin_score: 65.3
  mcp: *id062
  name: Fastly
  slug: fastly
  status: profiled
  tags: *id063
  url: /providers/fastly/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id064
  name: Fulcrum (getfulcrum.io)
  slug: getfulcrum
  status: queued for profiling
  tags: *id065
  url: null
- agent_band: agent-ready
  agent_readiness: 30.6
  band: thin
  in_catalog: true
  kin_score: 37.1
  mcp: *id066
  name: FullStory
  slug: fullstory
  status: profiled
  tags: *id067
  url: /providers/fullstory/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id068
  name: Gitar
  slug: gitar
  status: profiled
  tags: *id069
  url: /providers/gitar/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id070
  name: GitHub
  slug: github
  status: profiled
  tags: *id071
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id072
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id073
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id074
  name: Google BigQuery
  slug: google-bigquery
  status: profiled
  tags: *id075
  url: /providers/google-bigquery/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id076
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id077
  url: /providers/google-cloud-pubsub/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id078
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id079
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 60.6
  mcp: *id080
  name: Grafana
  slug: grafana-com
  status: profiled
  tags: *id081
  url: /providers/grafana-com/
- agent_band: agent-aware
  agent_readiness: 26.9
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id082
  name: Heap
  slug: heap
  status: profiled
  tags: *id083
  url: /providers/heap/
- agent_band: agent-ready
  agent_readiness: 63.8
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id084
  name: Hightouch
  slug: hightouch
  status: profiled
  tags: *id085
  url: /providers/hightouch/
- agent_band: agent-ready
  agent_readiness: 54.3
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id086
  name: Honeycomb
  slug: honeycomb
  status: profiled
  tags: *id087
  url: /providers/honeycomb/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.4
  mcp: *id088
  name: JetBrains IntelliJ
  slug: jetbrains
  status: profiled
  tags: *id089
  url: /providers/jetbrains/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id090
  name: Jira
  slug: jira
  status: profiled
  tags: *id091
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id092
  name: Kosli
  slug: kosli
  status: profiled
  tags: *id093
  url: /providers/kosli/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id094
  name: Last9
  slug: last9
  status: profiled
  tags: *id095
  url: /providers/last9/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id096
  name: Liquibase
  slug: liquibase
  status: queued for profiling
  tags: *id097
  url: null
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id098
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id099
  url: /providers/mattermost/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id100
  name: Mezmo (LogDNA)
  slug: mezmo
  status: profiled
  tags: *id101
  url: /providers/mezmo/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id102
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id103
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id104
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id105
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: strong
  in_catalog: true
  kin_score: 58.7
  mcp: *id106
  name: mParticle
  slug: mparticle
  status: profiled
  tags: *id107
  url: /providers/mparticle/
- agent_band: agent-ready
  agent_readiness: 58.8
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id108
  name: Netlify
  slug: netlify
  status: profiled
  tags: *id109
  url: /providers/netlify/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id110
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id111
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 34.0
  band: developing
  in_catalog: true
  kin_score: 52.5
  mcp: *id112
  name: ngrok
  slug: ngrok
  status: profiled
  tags: *id113
  url: /providers/ngrok/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id114
  name: Okta
  slug: okta
  status: profiled
  tags: *id115
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: strong
  in_catalog: true
  kin_score: 54.4
  mcp: *id116
  name: Okteto
  slug: okteto
  status: profiled
  tags: *id117
  url: /providers/okteto/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id118
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id119
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id120
  name: Osano
  slug: osano
  status: profiled
  tags: *id121
  url: /providers/osano/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id122
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id123
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 35.4
  band: strong
  in_catalog: true
  kin_score: 56.4
  mcp: *id124
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id125
  url: /providers/pendoio/
- agent_band: agent-aware
  agent_readiness: 22.7
  band: developing
  in_catalog: true
  kin_score: 44.0
  mcp: *id126
  name: Port
  slug: port-io
  status: profiled
  tags: *id127
  url: /providers/port-io/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id128
  name: Release (releaseapp.io)
  slug: release
  status: profiled
  tags: *id129
  url: /providers/release/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id130
  name: Resmo
  slug: resmo
  status: queued for profiling
  tags: *id131
  url: null
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 27.5
  mcp: *id132
  name: Roadie
  slug: roadie-io
  status: profiled
  tags: *id133
  url: /providers/roadie-io/
- agent_band: agent-ready
  agent_readiness: 58.1
  band: exemplar
  in_catalog: true
  kin_score: 78.5
  mcp: *id134
  name: RudderStack
  slug: rudderstack
  status: profiled
  tags: *id135
  url: /providers/rudderstack/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id136
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id137
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id138
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id139
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 69.5
  mcp: *id140
  name: SignalFx (Splunk Observability)
  slug: splunk-observability
  status: profiled
  tags: *id141
  url: /providers/splunk-observability/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id142
  name: Slack
  slug: slack
  status: profiled
  tags: *id143
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id144
  name: Sleuth
  slug: sleuth
  status: profiled
  tags: *id145
  url: /providers/sleuth/
- agent_band: agent-native
  agent_readiness: 45.8
  band: exemplar
  in_catalog: true
  kin_score: 81.1
  mcp: *id146
  name: Snowflake
  slug: snowflake
  status: profiled
  tags: *id147
  url: /providers/snowflake/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id148
  name: Snowplow
  slug: snowplow
  status: profiled
  tags: *id149
  url: /providers/snowplow/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id150
  name: SolarWinds AppOptics
  slug: solarwinds
  status: profiled
  tags: *id151
  url: /providers/solarwinds/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id152
  name: Split (Harness FME)
  slug: split
  status: profiled
  tags: *id153
  url: /providers/split/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id154
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id155
  url: /providers/splunk/
- agent_band: agent-ready
  agent_readiness: 55.6
  band: strong
  in_catalog: true
  kin_score: 57.8
  mcp: *id156
  name: Sprig
  slug: sprig
  status: profiled
  tags: *id157
  url: /providers/sprig/
- agent_band: agent-ready
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id158
  name: Statsig
  slug: statsig
  status: profiled
  tags: *id159
  url: /providers/statsig/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id160
  name: Tealium
  slug: tealium
  status: profiled
  tags: *id161
  url: /providers/tealium/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 43.6
  mcp: *id162
  name: Terraform
  slug: terraform
  status: profiled
  tags: *id163
  url: /providers/terraform/
- agent_band: agent-ready
  agent_readiness: 61.6
  band: exemplar
  in_catalog: true
  kin_score: 89.6
  mcp: *id164
  name: Tray.ai
  slug: tray-ai
  status: profiled
  tags: *id165
  url: /providers/tray-ai/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 75.6
  mcp: *id166
  name: Trello
  slug: trello
  status: profiled
  tags: *id167
  url: /providers/trello/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id168
  name: Twilio Segment
  slug: segment
  status: profiled
  tags: *id169
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: developing
  in_catalog: true
  kin_score: 45.4
  mcp: *id170
  name: Unleash
  slug: unleash
  status: profiled
  tags: *id171
  url: /providers/unleash/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id172
  name: Vercel
  slug: vercel
  status: profiled
  tags: *id173
  url: /providers/vercel/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id174
  name: VS Code
  slug: visual-studio-code
  status: profiled
  tags: *id175
  url: /providers/visual-studio-code/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id176
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id177
  url: /providers/zapier/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.8
  mcp: *id178
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id179
  url: /providers/zendesk/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id180
  name: Zeotap
  slug: zeotap
  status: profiled
  tags: *id181
  url: /providers/zeotap/
siblings:
- name: ConfigCat
  rows: 18
  url: /applications/feature-flags-experimentation/configcat/
- name: Flagsmith
  rows: 16
  url: /applications/feature-flags-experimentation/flagsmith/
- name: Flipt
  rows: 7
  url: /applications/feature-flags-experimentation/flipt/
- name: GrowthBook
  rows: 20
  url: /applications/feature-flags-experimentation/growthbook/
- name: Statsig
  rows: 33
  url: /applications/feature-flags-experimentation/statsig/
- name: Unleash
  rows: 4
  url: /applications/feature-flags-experimentation/unleash/
sitemap: true
title: 'LaunchDarkly: Feature Flags & Experimentation reference app'
---
