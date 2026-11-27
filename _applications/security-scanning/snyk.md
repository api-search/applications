---
app: Snyk
app_slug: snyk
app_url: https://snyk.io
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-250.10.20
  key: AE-250.10.20
  layer: domain
  name: Container Registries
  providers:
  - Amazon ECR
  - Azure Container Registry
  - DigitalOcean Container Registry
  - Docker Hub
  - GitHub Container Registry
  - GitLab Container Registry
  - Google Artifact Registry
  - Harbor
  - Quay
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: Turbo EA
  id: BC-4210.10
  key: continuous-integration-management
  layer: domain
  name: Continuous Integration Management
  providers:
  - AWS CodePipeline
  - Bitbucket Pipelines
  - CircleCI
  - GitHub Actions
  - Jenkins
  - Terraform Cloud
  url: /capabilities/continuous-integration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-250.10.10
  key: AE-250.10.10
  layer: domain
  name: Language Package Registries
  providers:
  - JFrog Artifactory
  - Sonatype Nexus Repository
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
- attribution: Turbo EA
  id: BC-4200.40.10
  key: BC-4200.40.10
  layer: domain
  name: Source Code Management
  providers:
  - Azure Repos / Azure Pipelines
  - Bitbucket
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: Software Construction Management
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - AWS
  - AWS CloudTrail Lake
  - Azure
  - Google Cloud
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - Jira
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 27
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://docs.snyk.io/sitemap.md
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.5
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-ecr
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Container Images
    - Container Registry
    - Containers
    url: /providers/amazon-ecr/
  layer: domain
  name: Amazon ECR
  provider: amazon-ecr
  says: lists Amazon ECR as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-amazon-elastic-container-registry-ecr.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id004
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: domain
  name: AWS
  provider: amazon-web-services
  says: lists AWS as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/aws-integration.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: exemplar
    in_catalog: true
    kin_score: 80.1
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudtrail
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Audit
    - CloudTrail
    - Compliance
    url: /providers/amazon-cloudtrail/
  layer: domain
  name: AWS CloudTrail Lake
  provider: amazon-cloudtrail
  says: lists AWS CloudTrail Lake as an integration
  source: https://docs.snyk.io/developer-tools/integrations/event-forwarding/aws-cloudtrail-lake.md
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
    agent_readiness: 27.8
    band: exemplar
    in_catalog: true
    kin_score: 71.6
    mcp: &id007
      source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
      status: documented
    slug: amazon-codepipeline
    status: profiled
    tags: &id008
    - Amazon
    - Amazon Web Services
    - CI/CD
    - Continuous Delivery
    url: /providers/amazon-codepipeline/
  layer: domain
  name: AWS CodePipeline
  provider: amazon-codepipeline
  says: lists AWS CodePipeline as an integration
  source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/aws-codepipeline-integration-by-adding-a-snyk-scan-stage.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id010
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: domain
  name: Azure
  provider: microsoft-azure
  says: lists Azure as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/azure-integration-for-cloud-configurations.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id011
      source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-container-registry
      status: verified
    slug: azure-container-registry
    status: profiled
    tags: &id012
    - Container Images
    - Containers
    - Docker
    - Microsoft Azure
    url: /providers/azure-container-registry/
  layer: domain
  name: Azure Container Registry
  provider: azure-container-registry
  says: lists Azure Container Registry as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-microsoft-azure-container-registry-acr.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: exemplar
    in_catalog: true
    kin_score: 81.9
    mcp: &id013
      source: https://github.com/microsoft/azure-devops-mcp
      status: verified
    slug: microsoft-azure-devops
    status: profiled
    tags: &id014
    - Agile
    - CI/CD
    - DevOps
    - Developer Tools
    url: /providers/microsoft-azure-devops/
  layer: domain
  name: Azure Repos / Azure Pipelines
  provider: microsoft-azure-devops
  says: lists Azure Repos / Azure Pipelines as an integration
  source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/azure-repositories-tfs.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
    mcp: &id015
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id016
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: lists Bitbucket as an integration
  source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/bitbucket-cloud.md
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
    agent_readiness: 34.3
    band: developing
    in_catalog: true
    kin_score: 51.1
    mcp: &id017
      source: https://www.atlassian.com/blog/bitbucket/connect-the-redesigned-atlassian-mcp-server-to-your-agentic-pipelines
      status: documented
    slug: bitbucket-pipelines
    status: profiled
    tags: &id018
    - Atlassian
    - CI/CD
    - DevOps
    - Pipelines
    url: /providers/bitbucket-pipelines/
  layer: domain
  name: Bitbucket Pipelines
  provider: bitbucket-pipelines
  says: lists Bitbucket Pipelines as an integration
  source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/bitbucket-pipelines-integration-using-a-snyk-pipe.md
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
    mcp: &id019
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id020
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
  layer: domain
  name: CircleCI
  provider: circleci
  says: lists CircleCI as an integration
  source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/circleci-integration-using-a-snyk-orb.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id021
      status: unchecked
    slug: digitalocean
    status: queued for profiling
    tags: &id022 []
    url: null
  layer: domain
  name: DigitalOcean Container Registry
  provider: digitalocean
  says: lists DigitalOcean Container Registry as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-digitalocean.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id023
      source: https://github.com/docker/hub-mcp
      status: verified
    slug: docker-hub
    status: profiled
    tags: &id024
    - Containers
    - DevOps
    - Docker
    - Registry
    url: /providers/docker-hub/
  layer: domain
  name: Docker Hub
  provider: docker-hub
  says: lists Docker Hub as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-docker-hub.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id025
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id026
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/github.md
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
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id027
      source: https://github.com/github/github-mcp-server
      status: documented
    slug: github-actions
    status: profiled
    tags: &id028
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/github-actions/
  layer: domain
  name: GitHub Actions
  provider: github-actions
  says: lists GitHub Actions as an integration
  source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/github-actions-for-snyk-setup-and-checking-for-vulnerabilities.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: strong
    in_catalog: true
    kin_score: 61.8
    mcp: &id029
      source: https://github.com/github/github-mcp-server
      status: documented
    slug: github-container-registry
    status: profiled
    tags: &id030
    - Container Images
    - Containers
    - GitHub
    - Packages
    url: /providers/github-container-registry/
  layer: domain
  name: GitHub Container Registry
  provider: github-container-registry
  says: lists GitHub Container Registry as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-github-container-registry.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.40.10
    key: BC-4200.40.10
    name: Source Code Management
    url: /capabilities/software-construction-management/
    via_parent: Software Construction Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id031
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id032
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: lists GitLab as an integration
  source: https://docs.snyk.io/developer-tools/integrations/scm-integrations/organization-level-integrations/gitlab.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id033
      status: unknown
    slug: gitlab-container-registry
    status: profiled
    tags: &id034
    - Container Images
    - Containers
    - GitLab
    - Registry
    url: /providers/gitlab-container-registry/
  layer: domain
  name: GitLab Container Registry
  provider: gitlab-container-registry
  says: lists GitLab Container Registry as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-gitlab-container-registry.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id035
      status: none
    slug: google-artifact-registry
    status: profiled
    tags: &id036
    - Artifacts
    - Containers
    - Google Cloud
    - Packages
    url: /providers/google-artifact-registry/
  layer: domain
  name: Google Artifact Registry
  provider: google-artifact-registry
  says: lists Google Artifact Registry as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-google-artifact-registry-gar.md
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id037
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id038
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: domain
  name: Google Cloud
  provider: google-cloud-platform
  says: lists Google Cloud as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-iac/cloud-platform-integrations/google-cloud-integration.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: strong
    in_catalog: true
    kin_score: 62.5
    mcp: &id039
      status: none
    slug: goharbor
    status: profiled
    tags: &id040
    - Artifacts
    - Container Registry
    - Containers
    - Vulnerability Scanning
    url: /providers/goharbor/
  layer: domain
  name: Harbor
  provider: goharbor
  says: lists Harbor as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-harbor-container-registry.md
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
    agent_readiness: 22.5
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id041
      source: https://github.com/jenkinsci/mcp-server-plugin
      status: verified
    slug: jenkins
    status: profiled
    tags: &id042
    - Automation
    - Build Server
    - CI/CD
    - Continuous Delivery
    url: /providers/jenkins/
  layer: domain
  name: Jenkins
  provider: jenkins
  says: lists Jenkins as an integration
  source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/jenkins-plugin-integration-with-snyk.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.1
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id043
      source: https://github.com/jfrog/jfrog-mcp-server
      status: verified
    slug: jfrog
    status: profiled
    tags: &id044
    - Artifactory
    - CI/CD
    - Container Registry
    - Developer Tools
    url: /providers/jfrog/
  layer: domain
  name: JFrog Artifactory
  provider: jfrog
  says: lists JFrog Artifactory as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-open-source/package-repository-integrations/artifactory-package-repository-connection-setup.md
  tier: declared
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id045
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id046
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://docs.snyk.io/developer-tools/integrations/jira-and-slack-integrations/jira-integration.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.0
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id047
      source: https://github.com/quay/quay-mcp-server
      status: verified
    slug: quay
    status: profiled
    tags: &id048
    - Container Images
    - Containers
    - Red Hat
    - Registry
    url: /providers/quay/
  layer: domain
  name: Quay
  provider: quay
  says: lists Quay as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-container/container-registry-integrations/integrate-with-quay-container-registry.md
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
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
  source: https://docs.snyk.io/developer-tools/integrations/jira-and-slack-integrations/slack-app.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.10
    key: AE-250.10.10
    name: Language Package Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id051
      source: https://github.com/sonatype/dependency-management-mcp-server
      status: verified
    slug: nexus
    status: profiled
    tags: &id052
    - Artifact Management
    - DevOps
    - Docker
    - Maven
    url: /providers/nexus/
  layer: domain
  name: Sonatype Nexus Repository
  provider: nexus
  says: lists Sonatype Nexus Repository as an integration
  source: https://docs.snyk.io/scan-fix-and-prevent/scan-with-snyk/snyk-open-source/package-repository-integrations/nexus-repository-manager-connection-setup.md
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
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id053
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id054
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
  layer: domain
  name: Terraform Cloud
  provider: terraform
  says: lists Terraform Cloud as an integration
  source: https://docs.snyk.io/developer-tools/integrations/snyk-ci-cd-integrations/terraform-cloud-integration-for-snyk-iac-using-run-tasks.md
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/snyk/
providers:
- agent_band: agent-ready
  agent_readiness: 29.5
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id001
  name: Amazon ECR
  slug: amazon-ecr
  status: profiled
  tags: *id002
  url: /providers/amazon-ecr/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id004
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: exemplar
  in_catalog: true
  kin_score: 80.1
  mcp: *id005
  name: AWS CloudTrail Lake
  slug: amazon-cloudtrail
  status: profiled
  tags: *id006
  url: /providers/amazon-cloudtrail/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: exemplar
  in_catalog: true
  kin_score: 71.6
  mcp: *id007
  name: AWS CodePipeline
  slug: amazon-codepipeline
  status: profiled
  tags: *id008
  url: /providers/amazon-codepipeline/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id009
  name: Azure
  slug: microsoft-azure
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id011
  name: Azure Container Registry
  slug: azure-container-registry
  status: profiled
  tags: *id012
  url: /providers/azure-container-registry/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: exemplar
  in_catalog: true
  kin_score: 81.9
  mcp: *id013
  name: Azure Repos / Azure Pipelines
  slug: microsoft-azure-devops
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id015
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id016
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 34.3
  band: developing
  in_catalog: true
  kin_score: 51.1
  mcp: *id017
  name: Bitbucket Pipelines
  slug: bitbucket-pipelines
  status: profiled
  tags: *id018
  url: /providers/bitbucket-pipelines/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 73.5
  mcp: *id019
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id020
  url: /providers/circleci/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id021
  name: DigitalOcean Container Registry
  slug: digitalocean
  status: queued for profiling
  tags: *id022
  url: null
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id023
  name: Docker Hub
  slug: docker-hub
  status: profiled
  tags: *id024
  url: /providers/docker-hub/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id025
  name: GitHub
  slug: github
  status: profiled
  tags: *id026
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id027
  name: GitHub Actions
  slug: github-actions
  status: profiled
  tags: *id028
  url: /providers/github-actions/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: strong
  in_catalog: true
  kin_score: 61.8
  mcp: *id029
  name: GitHub Container Registry
  slug: github-container-registry
  status: profiled
  tags: *id030
  url: /providers/github-container-registry/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id031
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id032
  url: /providers/gitlab/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id033
  name: GitLab Container Registry
  slug: gitlab-container-registry
  status: profiled
  tags: *id034
  url: /providers/gitlab-container-registry/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id035
  name: Google Artifact Registry
  slug: google-artifact-registry
  status: profiled
  tags: *id036
  url: /providers/google-artifact-registry/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id037
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id038
  url: /providers/google-cloud-platform/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: strong
  in_catalog: true
  kin_score: 62.5
  mcp: *id039
  name: Harbor
  slug: goharbor
  status: profiled
  tags: *id040
  url: /providers/goharbor/
- agent_band: agent-aware
  agent_readiness: 22.5
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id041
  name: Jenkins
  slug: jenkins
  status: profiled
  tags: *id042
  url: /providers/jenkins/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id043
  name: JFrog Artifactory
  slug: jfrog
  status: profiled
  tags: *id044
  url: /providers/jfrog/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id045
  name: Jira
  slug: jira
  status: profiled
  tags: *id046
  url: /providers/jira/
- agent_band: agent-aware
  agent_readiness: 27.0
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id047
  name: Quay
  slug: quay
  status: profiled
  tags: *id048
  url: /providers/quay/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id049
  name: Slack
  slug: slack
  status: profiled
  tags: *id050
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id051
  name: Sonatype Nexus Repository
  slug: nexus
  status: profiled
  tags: *id052
  url: /providers/nexus/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id053
  name: Terraform Cloud
  slug: terraform
  status: profiled
  tags: *id054
  url: /providers/terraform/
siblings:
- name: DefectDojo
  rows: 11
  url: /applications/security-scanning/defectdojo/
- name: Nuclei
  rows: 18
  url: /applications/security-scanning/nuclei/
- name: OWASP Dependency-Track
  rows: 22
  url: /applications/security-scanning/owasp-dependency-track/
- name: Tenable
  rows: 45
  url: /applications/security-scanning/tenable/
- name: Trivy
  rows: 4
  url: /applications/security-scanning/trivy/
- name: Wazuh
  rows: 17
  url: /applications/security-scanning/wazuh/
sitemap: true
title: 'Snyk: Security Scanning & Vulnerability Management reference app'
---
