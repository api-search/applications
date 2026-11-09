---
app: Postman
app_slug: postman
app_url: https://www.postman.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-909
  key: AE-909
  layer: domain
  name: API Gateways
  providers:
  - Apigee
  - AWS API Gateway
  - Azure API Management
  url: /capabilities/api-consumption-governance/
  via_parent: API Consumption Governance
- attribution: Turbo EA
  id: BC-4270.20.10
  key: BC-4270.20.10
  layer: domain
  name: SDK Generation & Release
  providers:
  - APIMatic
  url: /capabilities/sdk-client-library-management/
  via_parent: SDK & Client Library Management
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - PagerDuty
  - Splunk On-Call (VictorOps)
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
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
  - New Relic
  - Splunk
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Jira
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.30
  key: release-engineering-management
  layer: common
  name: Release Engineering Management
  providers:
  - CircleCI
  - Jenkins
  - Travis CI
  url: /capabilities/release-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: common
  name: Software Construction Management
  providers:
  - Azure DevOps
  - Bitbucket
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4290.60.20
  key: BC-4290.60.20
  layer: common
  name: Uptime Disclosure
  providers:
  - Statuspage
  url: /capabilities/service-resilience-commitment-management/
  via_parent: Service Resilience Commitment Management
category:
  id: api-management-gateway
  name: API Management & Gateways
  url: /applications/api-management-gateway/
counts:
  declared: 20
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://learning.postman.com/v11/docs/integrations/available-integrations/postman-integrations.md
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.7
    band: exemplar
    in_catalog: true
    kin_score: 69.6
    mcp: &id001
      source: https://cloud.google.com/apigee/docs/api-platform/apigee-mcp/apigee-mcp-overview
      status: documented
    slug: apigee
    status: profiled
    tags: &id002
    - AI Agents
    - Advanced API Security
    - Analytics
    - Apigee
    url: /providers/apigee/
  layer: domain
  name: Apigee
  provider: apigee
  says: lists Apigee as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/apigee-api-management/deploying-an-api-apigee.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4270.20.10
    key: BC-4270.20.10
    name: SDK Generation & Release
    url: /capabilities/sdk-client-library-management/
    via_parent: SDK & Client Library Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.9
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id003
      source: https://github.com/apimatic/apimatic-validator-mcp
      status: verified
    slug: apimatic
    status: profiled
    tags: &id004
    - API Transformation
    - Code Generation
    - Developer Experience
    - Developer Tools
    url: /providers/apimatic/
  layer: domain
  name: APIMatic
  provider: apimatic
  says: lists APIMatic as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/apimatic.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.1
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id005
      status: none
    slug: aws-api-gateway
    status: profiled
    tags: &id006
    - API Gateway
    - Amazon Web Services
    - Cloud
    - REST
    url: /providers/aws-api-gateway/
  layer: domain
  name: AWS API Gateway
  provider: aws-api-gateway
  says: lists AWS API Gateway as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/aws-api-gateway.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-909
    key: AE-909
    name: API Gateways
    url: /capabilities/api-consumption-governance/
    via_parent: API Consumption Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.0
    band: exemplar
    in_catalog: true
    kin_score: 80.3
    mcp: &id007
      source: https://learn.microsoft.com/en-us/azure/api-management/export-rest-mcp-server
      status: verified
    slug: microsoft-azure-api-management
    status: profiled
    tags: &id008
    - A2A
    - AI Gateway
    - API Center
    - API Gateway
    url: /providers/microsoft-azure-api-management/
  layer: domain
  name: Azure API Management
  provider: microsoft-azure-api-management
  says: lists Azure API Management as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/azure-api-management/deploying-an-api-azure.md
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
    mcp: &id009
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id010
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: common
  name: Azure DevOps
  provider: microsoft-azure-devops
  says: lists Azure DevOps as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/azure-devops.md
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
    mcp: &id011
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id012
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: common
  name: Bitbucket
  provider: bitbucket
  says: lists Bitbucket as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/bitbucket.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.1
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id013
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id014
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
  layer: common
  name: CircleCI
  provider: circleci
  says: lists CircleCI as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/circleci.md
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
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/datadog.md
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
    mcp: &id017
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id018
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/github/overview.md
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
    mcp: &id019
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id020
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/gitlab.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.0
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id021
      source: https://github.com/jenkinsci/mcp-server-plugin
      status: verified
    slug: jenkins
    status: profiled
    tags: &id022
    - Automation
    - Build Server
    - CI/CD
    - Continuous Delivery
    url: /providers/jenkins/
  layer: common
  name: Jenkins
  provider: jenkins
  says: lists Jenkins as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/jenkins.md
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
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/jira/overview.md
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
    mcp: &id025
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id026
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/microsoft-teams.md
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
    mcp: &id027
      source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
      status: verified
    slug: new-relic
    status: profiled
    tags: &id028
    - APM
    - Analysis
    - Analytics
    - DevOps
    url: /providers/new-relic/
  layer: common
  name: New Relic
  provider: new-relic
  says: lists New Relic as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/new-relic.md
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
    mcp: &id029
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id030
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: common
  name: PagerDuty
  provider: pagerduty
  says: lists PagerDuty as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/pagerduty.md
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
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/slack.md
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
    mcp: &id033
      status: none
    slug: splunk
    status: profiled
    tags: &id034
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: common
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/splunk.md
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.8
    mcp: &id035
      status: none
    slug: victorops
    status: profiled
    tags: &id036
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: common
  name: Splunk On-Call (VictorOps)
  provider: victorops
  says: lists Splunk On-Call (VictorOps) as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/splunk-on-call.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4290.60.20
    key: BC-4290.60.20
    name: Uptime Disclosure
    url: /capabilities/service-resilience-commitment-management/
    via_parent: Service Resilience Commitment Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 35.1
    mcp: &id037
      status: none
    slug: statuspage
    status: profiled
    tags: &id038
    - Incident Communication
    - Incident Management
    - Status Pages
    - Uptime
    url: /providers/statuspage/
  layer: common
  name: Statuspage
  provider: statuspage
  says: lists Statuspage as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/statuspage.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.30
    key: release-engineering-management
    name: Release Engineering Management
    url: /capabilities/release-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 32.1
    mcp: &id039
      status: none
    slug: travis-ci
    status: profiled
    tags: &id040
    - Builds
    - CI/CD
    - DevOps
    - Open Source
    url: /providers/travis-ci/
  layer: common
  name: Travis CI
  provider: travis-ci
  says: lists Travis CI as an integration
  source: https://learning.postman.com/v11/docs/integrations/available-integrations/ci-integrations/travis-ci.md
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/api-management-gateway/postman/
providers:
- agent_band: agent-ready
  agent_readiness: 31.7
  band: exemplar
  in_catalog: true
  kin_score: 69.6
  mcp: *id001
  name: Apigee
  slug: apigee
  status: profiled
  tags: *id002
  url: /providers/apigee/
- agent_band: agent-ready
  agent_readiness: 49.9
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id003
  name: APIMatic
  slug: apimatic
  status: profiled
  tags: *id004
  url: /providers/apimatic/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id005
  name: AWS API Gateway
  slug: aws-api-gateway
  status: profiled
  tags: *id006
  url: /providers/aws-api-gateway/
- agent_band: agent-ready
  agent_readiness: 31.0
  band: exemplar
  in_catalog: true
  kin_score: 80.3
  mcp: *id007
  name: Azure API Management
  slug: microsoft-azure-api-management
  status: profiled
  tags: *id008
  url: /providers/microsoft-azure-api-management/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id009
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 36.0
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id011
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id012
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 56.1
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id013
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id014
  url: /providers/circleci/
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
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id017
  name: GitHub
  slug: github
  status: profiled
  tags: *id018
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 55.6
  band: exemplar
  in_catalog: true
  kin_score: 79.6
  mcp: *id019
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id020
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id021
  name: Jenkins
  slug: jenkins
  status: profiled
  tags: *id022
  url: /providers/jenkins/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id023
  name: Jira
  slug: jira
  status: profiled
  tags: *id024
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id025
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id026
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 45.7
  band: exemplar
  in_catalog: true
  kin_score: 76.5
  mcp: *id027
  name: New Relic
  slug: new-relic
  status: profiled
  tags: *id028
  url: /providers/new-relic/
- agent_band: agent-ready
  agent_readiness: 48.9
  band: developing
  in_catalog: true
  kin_score: 51.2
  mcp: *id029
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id030
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id033
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id034
  url: /providers/splunk/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.8
  mcp: *id035
  name: Splunk On-Call (VictorOps)
  slug: victorops
  status: profiled
  tags: *id036
  url: /providers/victorops/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 35.1
  mcp: *id037
  name: Statuspage
  slug: statuspage
  status: profiled
  tags: *id038
  url: /providers/statuspage/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 32.1
  mcp: *id039
  name: Travis CI
  slug: travis-ci
  status: profiled
  tags: *id040
  url: /providers/travis-ci/
siblings:
- name: Apache APISIX
  rows: 36
  url: /applications/api-management-gateway/apache-apisix/
- name: Hoppscotch
  rows: 4
  url: /applications/api-management-gateway/hoppscotch/
- name: Kong Gateway
  rows: 17
  url: /applications/api-management-gateway/kong-gateway/
- name: KrakenD CE
  rows: 12
  url: /applications/api-management-gateway/krakend-ce/
- name: Traefik Proxy
  rows: 15
  url: /applications/api-management-gateway/traefik-proxy/
- name: Tyk Gateway + Tyk Pump
  rows: 24
  url: /applications/api-management-gateway/tyk-gateway-tyk-pump/
- name: Zuplo
  rows: 36
  url: /applications/api-management-gateway/zuplo/
sitemap: true
title: 'Postman: API Management & Gateways reference app'
---
