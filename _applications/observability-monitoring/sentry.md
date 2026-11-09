---
app: Sentry
app_slug: sentry
app_url: https://github.com/getsentry/sentry
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: domain
  name: IT Infrastructure Management
  providers:
  - AWS Lambda
  - boto3
  - google-cloud-build
  - google-cloud-functions
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - Opsgenie
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Discord
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Datadog
  - Google Cloud
  - google-cloud-logging
  - Splunk
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - google-cloud-kms
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - maxminddb
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon SQS
  - google-cloud-pubsub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - google-cloud-bigtable
  - google-cloud-spanner
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - Bitbucket
  - GitHub
  - GitLab
  - Perforce
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - Azure DevOps
  - Jira
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - google-cloud-storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-100.70.10
  key: AE-100.70.10
  layer: agent
  name: Coding Agents
  providers:
  - Claude Code
  - Cursor
  - GitHub Copilot
  url: /capabilities/vertical-agents/
  via_parent: Vertical Agents
category:
  id: observability-monitoring
  name: Observability, Monitoring & Status Pages
  url: /applications/observability-monitoring/
counts:
  declared: 0
  observed: 31
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
- route: source code
  url: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
- route: source code
  url: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
integrations:
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
    agent_readiness: 31.1
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: common
  name: Amazon SQS
  provider: amazon-sqs
  says: ships the Amazon SQS SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 45.6
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id003
      source: https://github.com/awslabs/mcp/tree/main/src/lambda-tool-mcp-server
      status: verified
    slug: aws-lambda
    status: profiled
    tags: &id004
    - Logging
    - Monitoring
    - Observability
    - Serverless
    url: /providers/aws-lambda/
  layer: domain
  name: AWS Lambda
  provider: aws-lambda
  says: ships the AWS Lambda SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
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
  layer: common
  name: Azure DevOps
  provider: microsoft-azure-devops
  says: ships the Azure DevOps SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
  layer: common
  name: Bitbucket
  provider: bitbucket
  says: ships the Bitbucket SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.8
    band: strong
    in_catalog: true
    kin_score: 60.5
    mcp: &id009
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id010
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: boto3
  provider: amazon-web-services
  says: ships the boto3 SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id011
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id012
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Claude Code
  provider: anthropic
  says: ships the Claude Code SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id013
      status: none
    slug: cursor
    status: profiled
    tags: &id014
    - Agents
    - Artificial Intelligence
    - Code Editor
    - Developer Tools
    url: /providers/cursor/
  layer: agent
  name: Cursor
  provider: cursor
  says: ships the Cursor SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    mcp: &id015
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id016
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: ships the Datadog SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id017
      status: none
    slug: discord
    status: profiled
    tags: &id018
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    mcp: &id019
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id020
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-100.70.10
    key: AE-100.70.10
    name: Coding Agents
    url: /capabilities/vertical-agents/
    via_parent: Vertical Agents
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.0
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id021
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github-copilot
    status: profiled
    tags: &id022
    - Agents
    - Artificial Intelligence
    - Code Generation
    - Code Review
    url: /providers/github-copilot/
  layer: agent
  name: GitHub Copilot
  provider: github-copilot
  says: ships the GitHub Copilot SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    mcp: &id023
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id024
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    agent_readiness: 50.7
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id025
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id026
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: domain
  name: Google Cloud
  provider: google-cloud-platform
  says: ships the Google Cloud SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id027
      source: https://docs.cloud.google.com/bigtable/docs/use-bigtable-mcp
      status: verified
    slug: google-cloud-bigtable
    status: profiled
    tags: &id028
    - Bigtable
    - Database
    - Google Cloud
    - NoSQL
    url: /providers/google-cloud-bigtable/
  layer: common
  name: google-cloud-bigtable
  provider: google-cloud-bigtable
  says: ships the google-cloud-bigtable SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id029
      status: none
    slug: google-cloud-build
    status: profiled
    tags: &id030
    - Build Automation
    - CI/CD
    - Container Build
    - Continuous Delivery
    url: /providers/google-cloud-build/
  layer: common
  name: google-cloud-build
  provider: google-cloud-build
  says: ships the google-cloud-build SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.2
    mcp: &id031
      status: none
    slug: google-cloud-functions
    status: profiled
    tags: &id032
    - Event-Driven
    - Functions
    - Google Cloud
    - Serverless
    url: /providers/google-cloud-functions/
  layer: domain
  name: google-cloud-functions
  provider: google-cloud-functions
  says: ships the google-cloud-functions SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 53.2
    mcp: &id033
      status: none
    slug: google-cloud-kms
    status: profiled
    tags: &id034
    - Cryptography
    - Encryption
    - Google Cloud
    - Key Management
    url: /providers/google-cloud-kms/
  layer: common
  name: google-cloud-kms
  provider: google-cloud-kms
  says: ships the google-cloud-kms SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
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
    agent_readiness: 50.0
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id035
      source: https://raw.githubusercontent.com/googleapis/gcloud-mcp/main/README.md
      status: verified
    slug: google-cloud-logging
    status: profiled
    tags: &id036
    - Cloud
    - Logging
    - Monitoring
    - Observability
    url: /providers/google-cloud-logging/
  layer: domain
  name: google-cloud-logging
  provider: google-cloud-logging
  says: ships the google-cloud-logging SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
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
    mcp: &id037
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id038
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
  layer: common
  name: google-cloud-pubsub
  provider: google-cloud-pubsub
  says: ships the google-cloud-pubsub SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id039
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-spanner
    status: profiled
    tags: &id040
    - Database
    - Distributed
    - Google Cloud
    - Relational
    url: /providers/google-cloud-spanner/
  layer: common
  name: google-cloud-spanner
  provider: google-cloud-spanner
  says: ships the google-cloud-spanner SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
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
    mcp: &id041
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id042
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: google-cloud-storage
  provider: gcp-cloud-storage
  says: ships the google-cloud-storage SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id043
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id044
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 33.3
    mcp: &id045
      status: none
    slug: maxmind
    status: profiled
    tags: &id046
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: maxminddb
  provider: maxmind
  says: ships the maxminddb SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
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
    mcp: &id047
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id048
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.1
    band: developing
    in_catalog: true
    kin_score: 48.9
    mcp: &id049
      status: none
    slug: opsgenie
    status: profiled
    tags: &id050
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    mcp: &id051
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id052
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    agent_readiness: 30.4
    band: developing
    in_catalog: true
    kin_score: 46.8
    mcp: &id053
      source: https://github.com/perforce/p4mcp-server
      status: verified
    slug: perforce
    status: profiled
    tags: &id054
    - Automation
    - DevOps
    - Project Management
    - Version Control
    url: /providers/perforce/
  layer: common
  name: Perforce
  provider: perforce
  says: ships the Perforce SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id055
      status: none
    slug: segment
    status: profiled
    tags: &id056
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
  tier: observed
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
    mcp: &id057
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id058
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations
  tier: observed
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
    mcp: &id059
      status: none
    slug: splunk
    status: profiled
    tags: &id060
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: ships the Splunk SDK or integration code
  source: https://github.com/getsentry/sentry/tree/master/src/sentry/integrations/data_forwarding
  tier: observed
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
    mcp: &id061
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id062
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: stripe
  provider: stripe
  says: ships the stripe SDK or integration code
  source: https://raw.githubusercontent.com/getsentry/sentry/master/pyproject.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/observability-monitoring/sentry/
providers:
- agent_band: agent-ready
  agent_readiness: 31.1
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id001
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id002
  url: /providers/amazon-sqs/
- agent_band: agent-native
  agent_readiness: 45.6
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id003
  name: AWS Lambda
  slug: aws-lambda
  status: profiled
  tags: *id004
  url: /providers/aws-lambda/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id005
  name: Azure DevOps
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
  agent_readiness: 40.8
  band: strong
  in_catalog: true
  kin_score: 60.5
  mcp: *id009
  name: boto3
  slug: amazon-web-services
  status: profiled
  tags: *id010
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id011
  name: Claude Code
  slug: anthropic
  status: profiled
  tags: *id012
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id013
  name: Cursor
  slug: cursor
  status: profiled
  tags: *id014
  url: /providers/cursor/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id015
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id016
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id017
  name: Discord
  slug: discord
  status: profiled
  tags: *id018
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id019
  name: GitHub
  slug: github
  status: profiled
  tags: *id020
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 49.0
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id021
  name: GitHub Copilot
  slug: github-copilot
  status: profiled
  tags: *id022
  url: /providers/github-copilot/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id023
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id024
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 50.7
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id025
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id026
  url: /providers/google-cloud-platform/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id027
  name: google-cloud-bigtable
  slug: google-cloud-bigtable
  status: profiled
  tags: *id028
  url: /providers/google-cloud-bigtable/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id029
  name: google-cloud-build
  slug: google-cloud-build
  status: profiled
  tags: *id030
  url: /providers/google-cloud-build/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.2
  mcp: *id031
  name: google-cloud-functions
  slug: google-cloud-functions
  status: profiled
  tags: *id032
  url: /providers/google-cloud-functions/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 53.2
  mcp: *id033
  name: google-cloud-kms
  slug: google-cloud-kms
  status: profiled
  tags: *id034
  url: /providers/google-cloud-kms/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id035
  name: google-cloud-logging
  slug: google-cloud-logging
  status: profiled
  tags: *id036
  url: /providers/google-cloud-logging/
- agent_band: agent-aware
  agent_readiness: 25.6
  band: thin
  in_catalog: true
  kin_score: 38.7
  mcp: *id037
  name: google-cloud-pubsub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id038
  url: /providers/google-cloud-pubsub/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id039
  name: google-cloud-spanner
  slug: google-cloud-spanner
  status: profiled
  tags: *id040
  url: /providers/google-cloud-spanner/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id041
  name: google-cloud-storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id042
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id043
  name: Jira
  slug: jira
  status: profiled
  tags: *id044
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 33.3
  mcp: *id045
  name: maxminddb
  slug: maxmind
  status: profiled
  tags: *id046
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id047
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id048
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 27.1
  band: developing
  in_catalog: true
  kin_score: 48.9
  mcp: *id049
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id050
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id051
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id052
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 30.4
  band: developing
  in_catalog: true
  kin_score: 46.8
  mcp: *id053
  name: Perforce
  slug: perforce
  status: profiled
  tags: *id054
  url: /providers/perforce/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id055
  name: Segment
  slug: segment
  status: profiled
  tags: *id056
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id057
  name: Slack
  slug: slack
  status: profiled
  tags: *id058
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id059
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id060
  url: /providers/splunk/
- agent_band: agent-native
  agent_readiness: 58.5
  band: exemplar
  in_catalog: true
  kin_score: 81.5
  mcp: *id061
  name: stripe
  slug: stripe
  status: profiled
  tags: *id062
  url: /providers/stripe/
siblings:
- name: Datadog
  rows: 21
  url: /applications/observability-monitoring/datadog/
- name: Gatus
  rows: 38
  url: /applications/observability-monitoring/gatus/
- name: Grafana
  rows: 30
  url: /applications/observability-monitoring/grafana/
- name: Netdata
  rows: 22
  url: /applications/observability-monitoring/netdata/
- name: Prometheus Alertmanager
  rows: 15
  url: /applications/observability-monitoring/prometheus-alertmanager/
- name: Uptime Kuma
  rows: 50
  url: /applications/observability-monitoring/uptime-kuma/
sitemap: true
title: 'Sentry: Observability, Monitoring & Status Pages reference app'
---
