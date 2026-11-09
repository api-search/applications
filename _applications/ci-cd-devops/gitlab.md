---
app: GitLab
app_slug: gitlab
app_url: https://gitlab.com/gitlab-org/gitlab
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: domain
  name: Software Product Engineering Management
  providers:
  - jira-ruby
  - Asana
  - Assembla
  - ClickUp
  - IBM Engineering Workflow Management
  - JetBrains YouTrack
  - Linear
  - Pivotal Tracker
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200.50
  key: software-quality-engineering
  layer: domain
  name: Software Quality Engineering
  providers:
  - Diffblue Cover
  url: /capabilities/software-quality-engineering/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210
  key: software-release-deployment-management
  layer: domain
  name: Software Release & Deployment Management
  providers:
  - Atlassian Bamboo
  - Buildkite
  - JetBrains TeamCity
  url: /capabilities/software-release-deployment-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.40
  key: vulnerability-management
  layer: domain
  name: Vulnerability Management
  providers:
  - GitGuardian
  url: /capabilities/vulnerability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - akismet
  - recaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50
  key: it-infrastructure-management
  layer: common
  name: IT Infrastructure Management
  providers:
  - aws-sdk-cloudformation
  - google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin
  - google-apis-container_v1
  url: /capabilities/it-infrastructure-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - duo_api
  - google-apis-iam_v1
  - Beyond Identity
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - slack-messenger
  - Campfire (37signals)
  - Discord
  - Google Chat
  - Mattermost
  - Microsoft Teams
  - Pumble
  - Telegram
  - Unify Circuit
  - Webex Teams
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.30
  key: knowledge-sharing-collaboration-management
  layer: common
  name: Knowledge Sharing & Collaboration Management
  providers:
  - Confluence Cloud
  url: /capabilities/knowledge-sharing-collaboration-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.20
  key: AE-150.50.20
  layer: common
  name: Number Verification
  providers:
  - telesignenterprise
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - sentry-ruby / sentry-rails
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - snowplow-tracker
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Pushover
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.30
  key: release-engineering-management
  layer: common
  name: Release Engineering Management
  providers:
  - google-cloud-artifact_registry-v1
  - Packagist
  url: /capabilities/release-engineering-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4270.70
  key: software-marketplace-listing-management
  layer: common
  name: Software Marketplace Listing Management
  providers:
  - google-apis-androidpublisher_v3
  - Apple App Store Connect
  url: /capabilities/software-marketplace-listing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - fog-aliyun
  - fog-aws / aws-sdk-s3
  - fog-google / google-cloud-storage
  - gitlab-fog-azure-rm
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - omniauth-alicloud
  - omniauth-atlassian-oauth2 / atlassian-jwt
  - omniauth-auth0
  - omniauth-azure-activedirectory-v2
  - omniauth-github
  - omniauth-google-oauth2
  - omniauth-salesforce
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - aws-actionmailer-ses
  url: /capabilities/email/
  via_parent: Email
category:
  id: ci-cd-devops
  name: Code Hosting, CI/CD & DevOps
  url: /applications/ci-cd-devops/
counts:
  declared: 28
  observed: 26
credits: []
evidence:
- route: dependency manifest
  url: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
- route: integrations page
  url: https://docs.gitlab.com/user/project/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id004
      status: unchecked
    slug: akismet
    status: queued for profiling
    tags: &id005 []
    url: null
  layer: common
  name: akismet
  provider: akismet
  says: ships the akismet SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id012
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id013
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: aws-actionmailer-ses
  provider: amazon-ses
  says: ships the aws-actionmailer-ses SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 38.5
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id014
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudformation
    status: profiled
    tags: &id015
    - Amazon Web Services
    - CloudFormation
    - DevOps
    - Infrastructure as Code
    url: /providers/amazon-cloudformation/
  layer: common
  name: aws-sdk-cloudformation
  provider: amazon-cloudformation
  says: ships the aws-sdk-cloudformation SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 21.3
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id032
      status: none
    slug: duo-security
    status: profiled
    tags: &id033
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: common
  name: duo_api
  provider: duo-security
  says: ships the duo_api SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: &id001
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id034
      source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
      status: verified
    slug: alibabacloud
    status: profiled
    tags: &id035
    - Company
    url: /providers/alibabacloud/
  layer: common
  name: fog-aliyun
  provider: alibabacloud
  says: ships the fog-aliyun SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
    mcp: &id036
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id037
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: fog-aws / aws-sdk-s3
  provider: amazon-s3
  says: ships the fog-aws / aws-sdk-s3 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    mcp: &id038
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id039
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: fog-google / google-cloud-storage
  provider: gcp-cloud-storage
  says: ships the fog-google / google-cloud-storage SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id042
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id043
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: gitlab-fog-azure-rm
  provider: microsoft-azure-blob-storage
  says: ships the gitlab-fog-azure-rm SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id046
      status: none
    slug: google-play
    status: profiled
    tags: &id047
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: google-apis-androidpublisher_v3
  provider: google-play
  says: ships the google-apis-androidpublisher_v3 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 50.7
    band: strong
    in_catalog: true
    kin_score: 64.8
    mcp: &id048
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id049
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: common
  name: google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin
  provider: google-cloud-platform
  says: ships the google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id050
      source: https://github.com/GoogleCloudPlatform/gke-mcp
      status: verified
    slug: google-kubernetes-engine
    status: profiled
    tags: &id051
    - Cloud-Native
    - Containers
    - Google Cloud
    - Kubernetes
    url: /providers/google-kubernetes-engine/
  layer: common
  name: google-apis-container_v1
  provider: google-kubernetes-engine
  says: ships the google-apis-container_v1 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.5
    mcp: &id052
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-cloud-iam
    status: profiled
    tags: &id053
    - Google Cloud
    - Identity
    - Identity and Access Management
    - Permissions
    url: /providers/google-cloud-iam/
  layer: common
  name: google-apis-iam_v1
  provider: google-cloud-iam
  says: ships the google-apis-iam_v1 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
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
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 38.4
    mcp: &id054
      status: none
    slug: google-artifact-registry
    status: profiled
    tags: &id055
    - Artifacts
    - Containers
    - Google Cloud
    - Packages
    url: /providers/google-artifact-registry/
  layer: common
  name: google-cloud-artifact_registry-v1
  provider: google-artifact-registry
  says: ships the google-cloud-artifact_registry-v1 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    mcp: &id062
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id063
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: jira-ruby
  provider: jira
  says: ships the jira-ruby SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
  name: omniauth-alicloud
  provider: alibabacloud
  says: ships the omniauth-alicloud SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 42.6
    band: exemplar
    in_catalog: true
    kin_score: 79.9
    mcp: &id070
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: atlassian
    status: profiled
    tags: &id071
    - Code
    - Collaboration
    - Platform
    - Productivity
    url: /providers/atlassian/
  layer: common
  name: omniauth-atlassian-oauth2 / atlassian-jwt
  provider: atlassian
  says: ships the omniauth-atlassian-oauth2 / atlassian-jwt SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id072
      source: https://auth0.com/docs/get-started/auth0-mcp-server
      status: verified
    slug: auth0
    status: profiled
    tags: &id073
    - AI Agents
    - Auth0
    - Authentication
    - Authorization
    url: /providers/auth0/
  layer: common
  name: omniauth-auth0
  provider: auth0
  says: ships the omniauth-auth0 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id074
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id075
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: omniauth-azure-activedirectory-v2
  provider: microsoft-entra
  says: ships the omniauth-azure-activedirectory-v2 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: &id003
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id076
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id077
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: omniauth-github
  provider: github
  says: ships the omniauth-github SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id078
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id079
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: omniauth-google-oauth2
  provider: google-identity-platform
  says: ships the omniauth-google-oauth2 SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id080
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id081
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: omniauth-salesforce
  provider: salesforce
  says: ships the omniauth-salesforce SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id090
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id091
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: recaptcha
  provider: google-recaptcha
  says: ships the recaptcha SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    kin_score: 80.6
    mcp: &id092
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id093
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: sentry-ruby / sentry-rails
  provider: sentry-system
  says: ships the sentry-ruby / sentry-rails SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    mcp: &id094
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id095
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: slack-messenger
  provider: slack
  says: ships the slack-messenger SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
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
    agent_readiness: 19.0
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id096
      source: https://github.com/snowplow/snowplow-cli
      status: verified
    slug: snowplow
    status: profiled
    tags: &id097
    - Analytics Platform
    - Behavioral Data
    - Data Collection
    - Data Engineering
    url: /providers/snowplow/
  layer: common
  name: snowplow-tracker
  provider: snowplow
  says: ships the snowplow-tracker SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.20
    key: AE-150.50.20
    name: Number Verification
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 76.9
    mcp: &id100
      status: none
    slug: telesign
    status: profiled
    tags: &id101
    - Authentication
    - Communications
    - Fraud Prevention
    - Phone Intelligence
    url: /providers/telesign/
  layer: common
  name: telesignenterprise
  provider: telesign
  says: ships the telesignenterprise SDK or integration code
  source: https://gitlab.com/gitlab-org/gitlab/-/raw/master/Gemfile
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4270.70
    key: software-marketplace-listing-management
    name: Software Marketplace Listing Management
    url: /capabilities/software-marketplace-listing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id006
      status: none
    slug: apple
    status: profiled
    tags: &id007
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Apple App Store Connect
  provider: apple
  says: lists Apple App Store Connect as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id008
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id009
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_band: agent-aware
    agent_readiness: 14.4
    band: emerging
    in_catalog: true
    kin_score: 23.0
    mcp: &id010
      status: none
    slug: assembla
    status: profiled
    tags: &id011
    - Cloud Hosting
    - DevOps
    - Project Management
    - Version Control
    url: /providers/assembla/
  layer: domain
  name: Assembla
  provider: assembla
  says: lists Assembla as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210
    key: software-release-deployment-management
    name: Software Release & Deployment Management
    url: /capabilities/software-release-deployment-management/
    via_parent: null
  credit: null
  facts: *id002
  layer: domain
  name: Atlassian Bamboo
  provider: atlassian
  says: lists Atlassian Bamboo as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
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
    agent_readiness: 34.5
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id016
      source: https://github.com/gobeyondidentity/bi-mcp
      status: verified
    slug: beyond-identity
    status: profiled
    tags: &id017
    - Authentication
    - Identity
    - Passwordless
    - Zero Trust
    url: /providers/beyond-identity/
  layer: common
  name: Beyond Identity
  provider: beyond-identity
  says: lists Beyond Identity as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 50.6
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id018
      source: https://github.com/buildkite/buildkite-mcp-server
      status: verified
    slug: buildkite-com
    status: profiled
    tags: &id019
    - CI/CD
    - Continuous Delivery
    - Continuous Integration
    - DevOps
    url: /providers/buildkite-com/
  layer: domain
  name: Buildkite
  provider: buildkite-com
  says: lists Buildkite as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.5
    mcp: &id020
      status: unknown
    slug: campfire-37signals
    status: profiled
    tags: &id021
    - Chat
    - Collaboration
    - Open Source
    - Self-Hosted
    url: /providers/campfire-37signals/
  layer: common
  name: Campfire (37signals)
  provider: campfire-37signals
  says: lists Campfire (37signals) as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 57.0
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id022
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id023
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: domain
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    mcp: &id024
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: confluence
    status: profiled
    tags: &id025
    - Collaboration
    - Content Management
    - Documentation
    - Knowledge Base
    url: /providers/confluence/
  layer: common
  name: Confluence Cloud
  provider: confluence
  says: lists Confluence Cloud as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    mcp: &id026
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id027
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: common
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200.50
    key: software-quality-engineering
    name: Software Quality Engineering
    url: /capabilities/software-quality-engineering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.1
    band: emerging
    in_catalog: true
    kin_score: 25.3
    mcp: &id028
      source: https://github.com/diffblue/cover-mcp
      status: verified
    slug: diffblue
    status: profiled
    tags: &id029
    - Artificial Intelligence
    - Automation
    - Enterprise
    - Testing
    url: /providers/diffblue/
  layer: domain
  name: Diffblue Cover
  provider: diffblue
  says: lists Diffblue Cover as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 46.9
    mcp: &id030
      status: none
    slug: discord
    status: profiled
    tags: &id031
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: common
  name: Discord
  provider: discord
  says: lists Discord as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.2
    band: minimal
    in_catalog: true
    kin_score: 6.4
    mcp: &id040
      source: https://github.com/GitGuardian/ggmcp
      status: verified
    slug: gitguardian
    status: profiled
    tags: &id041
    - Public APIs
    - Security
    url: /providers/gitguardian/
  layer: domain
  name: GitGuardian
  provider: gitguardian
  says: lists GitGuardian as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
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
  says: lists GitHub as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 51.6
    mcp: &id044
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id045
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: common
  name: Google Chat
  provider: google-chat
  says: lists Google Chat as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 64.9
    mcp: &id056
      source: https://github.com/IBM/mcp
      status: verified
    slug: ibm
    status: profiled
    tags: &id057
    - API Management
    - Artificial Intelligence
    - Database
    - IBM
    url: /providers/ibm/
  layer: domain
  name: IBM Engineering Workflow Management
  provider: ibm
  says: lists IBM Engineering Workflow Management as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 21.3
    band: developing
    in_catalog: true
    kin_score: 47.0
    mcp: &id058
      source: https://github.com/JetBrains/teamcity-mcp
      status: verified
    slug: teamcity
    status: profiled
    tags: &id059
    - Build Automation
    - CI/CD
    - Continuous Integration
    - Deployment
    url: /providers/teamcity/
  layer: domain
  name: JetBrains TeamCity
  provider: teamcity
  says: lists JetBrains TeamCity as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id060
      status: unchecked
    slug: youtrack
    status: queued for profiling
    tags: &id061 []
    url: null
  layer: domain
  name: JetBrains YouTrack
  provider: youtrack
  says: lists JetBrains YouTrack as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id064
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id065
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: domain
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    mcp: &id066
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id067
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: common
  name: Mattermost
  provider: mattermost
  says: lists Mattermost as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    mcp: &id068
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id069
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 23.6
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id082
      status: none
    slug: packagist
    status: profiled
    tags: &id083
    - Composer
    - Dependency Management
    - PHP
    - Package Registry
    url: /providers/packagist/
  layer: domain
  name: Packagist
  provider: packagist
  says: lists Packagist as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id084
      status: unchecked
    slug: pivotal-tracker
    status: queued for profiling
    tags: &id085 []
    url: null
  layer: domain
  name: Pivotal Tracker
  provider: pivotal-tracker
  says: lists Pivotal Tracker as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.7
    mcp: &id086
      source: https://pumble.com/help/integrations/automation-workflow-integrations/how-to-use-the-pumble-mcp-server/
      status: verified
    slug: pumble
    status: profiled
    tags: &id087
    - Company
    url: /providers/pumble/
  layer: common
  name: Pumble
  provider: pumble
  says: lists Pumble as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.0
    band: thin
    in_catalog: true
    kin_score: 29.2
    mcp: &id088
      status: none
    slug: pushover
    status: profiled
    tags: &id089
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: lists Pushover as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id098
      status: none
    slug: telegram
    status: profiled
    tags: &id099
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: lists Telegram as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id102
      status: unchecked
    slug: unify-circuit
    status: queued for profiling
    tags: &id103 []
    url: null
  layer: common
  name: Unify Circuit
  provider: unify-circuit
  says: lists Unify Circuit as an integration
  source: https://docs.gitlab.com/user/project/integrations/
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
    agent_readiness: 61.1
    band: strong
    in_catalog: true
    kin_score: 64.2
    mcp: &id104
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id105
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: common
  name: Webex Teams
  provider: webex
  says: lists Webex Teams as an integration
  source: https://docs.gitlab.com/user/project/integrations/
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ci-cd-devops/gitlab/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id004
  name: akismet
  slug: akismet
  status: queued for profiling
  tags: *id005
  url: null
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id006
  name: Apple App Store Connect
  slug: apple
  status: profiled
  tags: *id007
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id008
  name: Asana
  slug: asana
  status: profiled
  tags: *id009
  url: /providers/asana/
- agent_band: agent-aware
  agent_readiness: 14.4
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id010
  name: Assembla
  slug: assembla
  status: profiled
  tags: *id011
  url: /providers/assembla/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id012
  name: aws-actionmailer-ses
  slug: amazon-ses
  status: profiled
  tags: *id013
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 38.5
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id014
  name: aws-sdk-cloudformation
  slug: amazon-cloudformation
  status: profiled
  tags: *id015
  url: /providers/amazon-cloudformation/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id016
  name: Beyond Identity
  slug: beyond-identity
  status: profiled
  tags: *id017
  url: /providers/beyond-identity/
- agent_band: agent-ready
  agent_readiness: 50.6
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id018
  name: Buildkite
  slug: buildkite-com
  status: profiled
  tags: *id019
  url: /providers/buildkite-com/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.5
  mcp: *id020
  name: Campfire (37signals)
  slug: campfire-37signals
  status: profiled
  tags: *id021
  url: /providers/campfire-37signals/
- agent_band: agent-ready
  agent_readiness: 57.0
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id022
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id023
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id024
  name: Confluence Cloud
  slug: confluence
  status: profiled
  tags: *id025
  url: /providers/confluence/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id026
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id027
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 17.1
  band: emerging
  in_catalog: true
  kin_score: 25.3
  mcp: *id028
  name: Diffblue Cover
  slug: diffblue
  status: profiled
  tags: *id029
  url: /providers/diffblue/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 46.9
  mcp: *id030
  name: Discord
  slug: discord
  status: profiled
  tags: *id031
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id032
  name: duo_api
  slug: duo-security
  status: profiled
  tags: *id033
  url: /providers/duo-security/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id034
  name: fog-aliyun
  slug: alibabacloud
  status: profiled
  tags: *id035
  url: /providers/alibabacloud/
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id036
  name: fog-aws / aws-sdk-s3
  slug: amazon-s3
  status: profiled
  tags: *id037
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id038
  name: fog-google / google-cloud-storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id039
  url: /providers/gcp-cloud-storage/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: minimal
  in_catalog: true
  kin_score: 6.4
  mcp: *id040
  name: GitGuardian
  slug: gitguardian
  status: profiled
  tags: *id041
  url: /providers/gitguardian/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id042
  name: gitlab-fog-azure-rm
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id043
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 51.6
  mcp: *id044
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id045
  url: /providers/google-chat/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id046
  name: google-apis-androidpublisher_v3
  slug: google-play
  status: profiled
  tags: *id047
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 50.7
  band: strong
  in_catalog: true
  kin_score: 64.8
  mcp: *id048
  name: google-apis-compute_v1 / cloudresourcemanager / cloudbilling / sqladmin
  slug: google-cloud-platform
  status: profiled
  tags: *id049
  url: /providers/google-cloud-platform/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id050
  name: google-apis-container_v1
  slug: google-kubernetes-engine
  status: profiled
  tags: *id051
  url: /providers/google-kubernetes-engine/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.5
  mcp: *id052
  name: google-apis-iam_v1
  slug: google-cloud-iam
  status: profiled
  tags: *id053
  url: /providers/google-cloud-iam/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 38.4
  mcp: *id054
  name: google-cloud-artifact_registry-v1
  slug: google-artifact-registry
  status: profiled
  tags: *id055
  url: /providers/google-artifact-registry/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 64.9
  mcp: *id056
  name: IBM Engineering Workflow Management
  slug: ibm
  status: profiled
  tags: *id057
  url: /providers/ibm/
- agent_band: agent-aware
  agent_readiness: 21.3
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id058
  name: JetBrains TeamCity
  slug: teamcity
  status: profiled
  tags: *id059
  url: /providers/teamcity/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id060
  name: JetBrains YouTrack
  slug: youtrack
  status: queued for profiling
  tags: *id061
  url: null
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id062
  name: jira-ruby
  slug: jira
  status: profiled
  tags: *id063
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id064
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id065
  url: /providers/linear-app/
- agent_band: agent-aware
  agent_readiness: 25.7
  band: thin
  in_catalog: true
  kin_score: 37.2
  mcp: *id066
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id067
  url: /providers/mattermost/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id068
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id069
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: exemplar
  in_catalog: true
  kin_score: 79.9
  mcp: *id070
  name: omniauth-atlassian-oauth2 / atlassian-jwt
  slug: atlassian
  status: profiled
  tags: *id071
  url: /providers/atlassian/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id072
  name: omniauth-auth0
  slug: auth0
  status: profiled
  tags: *id073
  url: /providers/auth0/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id074
  name: omniauth-azure-activedirectory-v2
  slug: microsoft-entra
  status: profiled
  tags: *id075
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id076
  name: omniauth-github
  slug: github
  status: profiled
  tags: *id077
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id078
  name: omniauth-google-oauth2
  slug: google-identity-platform
  status: profiled
  tags: *id079
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id080
  name: omniauth-salesforce
  slug: salesforce
  status: profiled
  tags: *id081
  url: /providers/salesforce/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id082
  name: Packagist
  slug: packagist
  status: profiled
  tags: *id083
  url: /providers/packagist/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id084
  name: Pivotal Tracker
  slug: pivotal-tracker
  status: queued for profiling
  tags: *id085
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.7
  mcp: *id086
  name: Pumble
  slug: pumble
  status: profiled
  tags: *id087
  url: /providers/pumble/
- agent_band: agent-aware
  agent_readiness: 22.0
  band: thin
  in_catalog: true
  kin_score: 29.2
  mcp: *id088
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id089
  url: /providers/pushover/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id090
  name: recaptcha
  slug: google-recaptcha
  status: profiled
  tags: *id091
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id092
  name: sentry-ruby / sentry-rails
  slug: sentry-system
  status: profiled
  tags: *id093
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id094
  name: slack-messenger
  slug: slack
  status: profiled
  tags: *id095
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id096
  name: snowplow-tracker
  slug: snowplow
  status: profiled
  tags: *id097
  url: /providers/snowplow/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id098
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id099
  url: /providers/telegram/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 76.9
  mcp: *id100
  name: telesignenterprise
  slug: telesign
  status: profiled
  tags: *id101
  url: /providers/telesign/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id102
  name: Unify Circuit
  slug: unify-circuit
  status: queued for profiling
  tags: *id103
  url: null
- agent_band: agent-ready
  agent_readiness: 61.1
  band: strong
  in_catalog: true
  kin_score: 64.2
  mcp: *id104
  name: Webex Teams
  slug: webex
  status: profiled
  tags: *id105
  url: /providers/webex/
siblings:
- name: CircleCI
  rows: 54
  url: /applications/ci-cd-devops/circleci/
- name: Coolify
  rows: 21
  url: /applications/ci-cd-devops/coolify/
- name: Gitea
  rows: 24
  url: /applications/ci-cd-devops/gitea/
- name: GitHub
  rows: 6
  url: /applications/ci-cd-devops/github/
- name: Woodpecker CI
  rows: 3
  url: /applications/ci-cd-devops/woodpecker-ci/
sitemap: true
title: 'GitLab: Code Hosting, CI/CD & DevOps reference app'
---
