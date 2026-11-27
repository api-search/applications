---
app: Backstage
app_slug: backstage
app_url: https://github.com/backstage/backstage
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: domain
  name: Search and Discovery Management
  providers:
  - Elastic
  - Stack Overflow
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Azure DevOps
  - Bitbucket
  - Gerrit
  - Gitea
  - GitHub
  - GitLab
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - AWS
  - Google Cloud
  - PuppetDB
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Microsoft Graph
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.60.50
  key: BC-600.60.50
  layer: common
  name: Integration and API Management
  providers:
  - Amazon SQS
  - Apache Kafka
  - Google Cloud Pub/Sub
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
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
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Bitbucket
  - GitHub
  - GitLab
  - Google sign-in
  - OpenShift
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  - OpenStack Swift
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Atlassian
  - Auth0
  - AWS ALB
  - Azure Easy Auth
  - Cloudflare Access
  - Google Cloud IAP
  - Microsoft
  - Okta
  - OneLogin
  - VMware Cloud
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: developer-docs-portal
  name: Developer Docs & API Portals
  url: /applications/developer-docs-portal/
counts:
  declared: 0
  observed: 37
credits: []
evidence:
- route: source code
  url: https://github.com/backstage/backstage/tree/master/plugins
- route: source code
  url: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id006
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id007
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id008
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sqs
    status: profiled
    tags: &id009
    - Amazon Web Services
    - Cloud
    - Distributed Systems
    - Messaging
    url: /providers/amazon-sqs/
  layer: common
  name: Amazon SQS
  provider: amazon-sqs
  says: ships the Amazon SQS SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_readiness: 27.8
    band: developing
    in_catalog: true
    kin_score: 51.4
    mcp: &id010
      status: none
    slug: apache-kafka
    status: profiled
    tags: &id011
    - Apache Kafka
    - Distributed Systems
    - Event Streaming
    - Messaging
    url: /providers/apache-kafka/
  layer: common
  name: Apache Kafka
  provider: apache-kafka
  says: ships the Apache Kafka SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 79.8
    mcp: &id012
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: atlassian
    status: profiled
    tags: &id013
    - Code
    - Collaboration
    - Platform
    - Productivity
    url: /providers/atlassian/
  layer: common
  name: Atlassian
  provider: atlassian
  says: ships the Atlassian SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 39.5
    band: exemplar
    in_catalog: true
    kin_score: 71.8
    mcp: &id014
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id015
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: Auth0
  provider: auth0
  says: ships the Auth0 SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id016
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id017
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS
  provider: amazon-web-services
  says: ships the AWS SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: *id001
  layer: common
  name: AWS ALB
  provider: amazon-web-services
  says: ships the AWS ALB SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_readiness: 37.9
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id018
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id019
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    agent_readiness: 37.7
    band: exemplar
    in_catalog: true
    kin_score: 81.9
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
  says: ships the Azure DevOps SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id022
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id023
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: common
  name: Azure Easy Auth
  provider: microsoft-azure
  says: ships the Azure Easy Auth SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
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
  layer: common
  name: Bitbucket
  provider: bitbucket
  says: ships the Bitbucket SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: *id002
  layer: domain
  name: Bitbucket
  provider: bitbucket
  says: ships the Bitbucket SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id026
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id027
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare Access
  provider: cloudflare
  says: ships the Cloudflare Access SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id028
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: confluence
    status: profiled
    tags: &id029
    - Collaboration
    - Content Management
    - Documentation
    - Knowledge Base
    url: /providers/confluence/
  layer: common
  name: Confluence
  provider: confluence
  says: ships the Confluence SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id030
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id031
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elastic
  provider: elastic
  says: ships the Elastic SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.8
    mcp: &id032
      source: https://github.com/GerritCodeReview/gerrit-mcp-server
      status: verified
    slug: gerrit
    status: profiled
    tags: &id033
    - Code Review
    - Company
    - Open Source
    - Version Control
    url: /providers/gerrit/
  layer: domain
  name: Gerrit
  provider: gerrit
  says: ships the Gerrit SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id034
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id035
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
  layer: domain
  name: Gitea
  provider: gitea
  says: ships the Gitea SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: &id003
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id036
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id037
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: *id003
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts: &id004
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id038
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id039
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts: *id004
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50
    key: it-infrastructure-management
    name: IT Infrastructure Management
    url: /capabilities/it-infrastructure-management/
    via_parent: null
  credit: null
  facts: &id005
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id040
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id041
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: common
  name: Google Cloud
  provider: google-cloud-platform
  says: ships the Google Cloud SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: *id005
  layer: common
  name: Google Cloud IAP
  provider: google-cloud-platform
  says: ships the Google Cloud IAP SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_band: agent-ready
    agent_readiness: 38.0
    band: strong
    in_catalog: true
    kin_score: 64.1
    mcp: &id042
      source: https://docs.cloud.google.com/pubsub/docs/use-pubsub-mcp
      status: verified
    slug: google-cloud-pubsub
    status: profiled
    tags: &id043
    - Event-Driven
    - Google Cloud
    - Messaging
    - Pub/Sub
    url: /providers/google-cloud-pubsub/
  layer: common
  name: Google Cloud Pub/Sub
  provider: google-cloud-pubsub
  says: ships the Google Cloud Pub/Sub SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id044
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id045
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id046
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id047
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id048
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id049
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id050
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id051
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: common
  name: Microsoft Graph
  provider: microsoft-graph
  says: ships the Microsoft Graph SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id052
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id053
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: ships the Okta SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id054
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id055
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: common
  name: OneLogin
  provider: onelogin
  says: ships the OneLogin SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.9
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id056
      source: https://github.com/openshift/kubernetes-mcp-server
      status: verified
    slug: red-hat-openshift
    status: profiled
    tags: &id057
    - Containers
    - Enterprise
    - Hybrid Cloud
    - Kubernetes
    url: /providers/red-hat-openshift/
  layer: common
  name: OpenShift
  provider: red-hat-openshift
  says: ships the OpenShift SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 34.5
    mcp: &id058
      status: none
    slug: openstack
    status: profiled
    tags: &id059
    - Cloud Platform
    - Infrastructure-as-a-Service
    - Open Source
    - OpenStack
    url: /providers/openstack/
  layer: common
  name: OpenStack Swift
  provider: openstack
  says: ships the OpenStack Swift SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins/techdocs-node/src/stages/publish
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
    agent_readiness: 24.7
    band: thin
    in_catalog: true
    kin_score: 32.0
    mcp: &id060
      source: https://github.com/puppetlabs/puppetlabs-pe_mcp
      status: verified
    slug: puppet
    status: profiled
    tags: &id061
    - Automation
    - Configuration Management
    - DevOps
    - Enterprise
    url: /providers/puppet/
  layer: common
  name: PuppetDB
  provider: puppet
  says: ships the PuppetDB SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id062
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id063
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
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
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id064
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id065
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.3
    band: thin
    in_catalog: true
    kin_score: 36.6
    mcp: &id066
      source: https://github.com/StackExchange/Stack-MCP
      status: verified
    slug: stack-overflow
    status: profiled
    tags: &id067
    - Answers
    - Code
    - Developer Community
    - Developer Tools
    url: /providers/stack-overflow/
  layer: domain
  name: Stack Overflow
  provider: stack-overflow
  says: ships the Stack Overflow SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
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
    agent_readiness: 23.3
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id068
      status: none
    slug: vmware
    status: profiled
    tags: &id069
    - Cloud Computing
    - Container Management
    - Hybrid Cloud
    - Infrastructure
    url: /providers/vmware/
  layer: common
  name: VMware Cloud
  provider: vmware
  says: ships the VMware Cloud SDK or integration code
  source: https://github.com/backstage/backstage/tree/master/plugins
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/developer-docs-portal/backstage/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id006
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id007
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id008
  name: Amazon SQS
  slug: amazon-sqs
  status: profiled
  tags: *id009
  url: /providers/amazon-sqs/
- agent_band: agent-aware
  agent_readiness: 27.8
  band: developing
  in_catalog: true
  kin_score: 51.4
  mcp: *id010
  name: Apache Kafka
  slug: apache-kafka
  status: profiled
  tags: *id011
  url: /providers/apache-kafka/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 79.8
  mcp: *id012
  name: Atlassian
  slug: atlassian
  status: profiled
  tags: *id013
  url: /providers/atlassian/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: exemplar
  in_catalog: true
  kin_score: 71.8
  mcp: *id014
  name: Auth0
  slug: auth0
  status: profiled
  tags: *id015
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id016
  name: AWS
  slug: amazon-web-services
  status: profiled
  tags: *id017
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id018
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id019
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: exemplar
  in_catalog: true
  kin_score: 81.9
  mcp: *id020
  name: Azure DevOps
  slug: microsoft-azure-devops
  status: profiled
  tags: *id021
  url: /providers/microsoft-azure-devops/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id022
  name: Azure Easy Auth
  slug: microsoft-azure
  status: profiled
  tags: *id023
  url: /providers/microsoft-azure/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id024
  name: Bitbucket
  slug: bitbucket
  status: profiled
  tags: *id025
  url: /providers/bitbucket/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id026
  name: Cloudflare Access
  slug: cloudflare
  status: profiled
  tags: *id027
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id028
  name: Confluence
  slug: confluence
  status: profiled
  tags: *id029
  url: /providers/confluence/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id030
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id031
  url: /providers/elastic/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.8
  mcp: *id032
  name: Gerrit
  slug: gerrit
  status: profiled
  tags: *id033
  url: /providers/gerrit/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id034
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id035
  url: /providers/gitea/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id036
  name: GitHub
  slug: github
  status: profiled
  tags: *id037
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id038
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id039
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id040
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id041
  url: /providers/google-cloud-platform/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: strong
  in_catalog: true
  kin_score: 64.1
  mcp: *id042
  name: Google Cloud Pub/Sub
  slug: google-cloud-pubsub
  status: profiled
  tags: *id043
  url: /providers/google-cloud-pubsub/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id044
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id045
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id046
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id047
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id048
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id049
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id050
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id051
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id052
  name: Okta
  slug: okta
  status: profiled
  tags: *id053
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id054
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id055
  url: /providers/onelogin/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id056
  name: OpenShift
  slug: red-hat-openshift
  status: profiled
  tags: *id057
  url: /providers/red-hat-openshift/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 34.5
  mcp: *id058
  name: OpenStack Swift
  slug: openstack
  status: profiled
  tags: *id059
  url: /providers/openstack/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: thin
  in_catalog: true
  kin_score: 32.0
  mcp: *id060
  name: PuppetDB
  slug: puppet
  status: profiled
  tags: *id061
  url: /providers/puppet/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id062
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id063
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id064
  name: Slack
  slug: slack
  status: profiled
  tags: *id065
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 33.3
  band: thin
  in_catalog: true
  kin_score: 36.6
  mcp: *id066
  name: Stack Overflow
  slug: stack-overflow
  status: profiled
  tags: *id067
  url: /providers/stack-overflow/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id068
  name: VMware Cloud
  slug: vmware
  status: profiled
  tags: *id069
  url: /providers/vmware/
siblings:
- name: Docusaurus
  rows: 7
  url: /applications/developer-docs-portal/docusaurus/
- name: GitBook
  rows: 56
  url: /applications/developer-docs-portal/gitbook/
- name: Mintlify
  rows: 49
  url: /applications/developer-docs-portal/mintlify/
- name: ReadMe
  rows: 17
  url: /applications/developer-docs-portal/readme/
- name: Redocly
  rows: 16
  url: /applications/developer-docs-portal/redocly/
- name: Zudoku
  rows: 10
  url: /applications/developer-docs-portal/zudoku/
sitemap: true
title: 'Backstage: Developer Docs & API Portals reference app'
---
