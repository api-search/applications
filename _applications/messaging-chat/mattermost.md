---
app: Mattermost
app_slug: mattermost
app_url: https://github.com/mattermost/mattermost
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Microsoft Calendar / Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Jira
  url: /capabilities/project-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - GitLab
  - Google SSO
  - Office 365 / Entra ID SSO
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - GitHub
  url: /capabilities/software-construction-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - Pexip
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: common
  name: End-User Computing Management
  providers:
  - Microsoft Intune
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - Split (Harness FME)
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  - Splunk
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Azure Blob Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - AWS Marketplace metering
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Anthropic
  - Azure OpenAI
  - Cohere
  - Google Gemini
  - Google Vertex AI
  - Mistral AI
  - OpenAI
  - Scale AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: messaging-chat
  name: Messaging & Team Chat
  url: /applications/messaging-chat/
counts:
  declared: 7
  observed: 18
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.mattermost.rn/latest/
- route: dependency manifest
  url: https://github.com/mattermost/mattermost/blob/master/server/go.mod
- route: integrations page
  url: https://docs.mattermost.com/integrations-guide/popular-integrations.html
- route: source code
  url: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
- route: source code
  url: https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
- route: source code
  url: https://github.com/mattermost/mattermost/tree/master/server/einterfaces
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: Amazon Bedrock
  provider: amazon-bedrock
  says: ships the Amazon Bedrock SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id003
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id004
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id006
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: AWS Marketplace metering
  provider: amazon-web-services
  says: ships the AWS Marketplace metering SDK or integration code
  source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
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
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id008
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.9
    band: exemplar
    in_catalog: true
    kin_score: 68.3
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: agent
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.6
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id011
      status: none
    slug: cohere
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Embeddings
    - Natural Language Processing
    - Vector Search
    url: /providers/cohere/
  layer: agent
  name: Cohere
  provider: cohere
  says: ships the Cohere SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id015
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/mattermost/mattermost/tree/master/server/channels/app/oauthproviders
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id017
      status: none
    slug: google-admob
    status: profiled
    tags: &id018
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.mattermost.rn/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id019
      status: none
    slug: google-gemini
    status: profiled
    tags: &id020
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    mcp: &id021
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id022
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google SSO
  provider: google-identity-platform
  says: ships the Google SSO SDK or integration code
  source: https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 42.2
    band: strong
    in_catalog: true
    kin_score: 63.2
    mcp: &id023
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: agent
  name: Google Vertex AI
  provider: google-vertex-ai
  says: ships the Google Vertex AI SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id029
      status: none
    slug: microsoft-intune
    status: profiled
    tags: &id030
    - App Protection
    - Compliance
    - Device Configuration
    - Microsoft Azure
    url: /providers/microsoft-intune/
  layer: common
  name: Microsoft Intune
  provider: microsoft-intune
  says: ships the Microsoft Intune SDK or integration code
  source: https://github.com/mattermost/mattermost/tree/master/server/einterfaces
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id033
      status: none
    slug: mistral
    status: profiled
    tags: &id034
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: agent
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id035
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id036
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Office 365 / Entra ID SSO
  provider: microsoft-entra
  says: ships the Office 365 / Entra ID SSO SDK or integration code
  source: https://github.com/mattermost/mattermost/blob/master/server/public/model/config.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id037
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id038
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 71.1
    mcp: &id041
      status: none
    slug: scale-ai
    status: profiled
    tags: &id042
    - Data Engine
    - GenAI Platform
    - Labeling
    - RLHF
    url: /providers/scale-ai/
  layer: agent
  name: Scale AI
  provider: scale-ai
  says: ships the Scale AI SDK or integration code
  source: https://github.com/mattermost/mattermost-plugin-agents/blob/master/llm/service_types.go
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
    mcp: &id043
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id044
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
  tier: observed
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
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id045
      status: none
    slug: split
    status: profiled
    tags: &id046
    - Experimentation
    - Feature Flags
    - Feature Management
    - Rollouts
    url: /providers/split/
  layer: common
  name: Split (Harness FME)
  provider: split
  says: ships the Split (Harness FME) SDK or integration code
  source: https://github.com/mattermost/mattermost/blob/master/server/go.mod
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id013
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
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
    mcp: &id025
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id026
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
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
    mcp: &id027
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id028
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Microsoft Calendar / Outlook
  provider: microsoft-outlook
  says: lists Microsoft Calendar / Outlook as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id031
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id032
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: thin
    in_catalog: true
    kin_score: 31.7
    mcp: &id039
      status: none
    slug: pexip
    status: profiled
    tags: &id040
    - Cloud
    - Communications
    - Security
    - Video
    url: /providers/pexip/
  layer: domain
  name: Pexip
  provider: pexip
  says: lists Pexip as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
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
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id047
      status: none
    slug: splunk
    status: profiled
    tags: &id048
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id049
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id050
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://docs.mattermost.com/integrations-guide/popular-integrations.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/messaging-chat/mattermost/
providers:
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id001
  name: Amazon Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id002
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id003
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id004
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id005
  name: AWS Marketplace metering
  slug: amazon-web-services
  status: profiled
  tags: *id006
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id007
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id008
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id009
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-openai/
- agent_band: agent-ready
  agent_readiness: 40.6
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id011
  name: Cohere
  slug: cohere
  status: profiled
  tags: *id012
  url: /providers/cohere/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id013
  name: GitHub
  slug: github
  status: profiled
  tags: *id014
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id015
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id016
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id017
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id018
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id019
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id020
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id021
  name: Google SSO
  slug: google-identity-platform
  status: profiled
  tags: *id022
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id023
  name: Google Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id024
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id025
  name: Jira
  slug: jira
  status: profiled
  tags: *id026
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id027
  name: Microsoft Calendar / Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id028
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id029
  name: Microsoft Intune
  slug: microsoft-intune
  status: profiled
  tags: *id030
  url: /providers/microsoft-intune/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id031
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id032
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id033
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id034
  url: /providers/mistral/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id035
  name: Office 365 / Entra ID SSO
  slug: microsoft-entra
  status: profiled
  tags: *id036
  url: /providers/microsoft-entra/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id037
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id038
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.0
  band: thin
  in_catalog: true
  kin_score: 31.7
  mcp: *id039
  name: Pexip
  slug: pexip
  status: profiled
  tags: *id040
  url: /providers/pexip/
- agent_band: agent-native
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 71.1
  mcp: *id041
  name: Scale AI
  slug: scale-ai
  status: profiled
  tags: *id042
  url: /providers/scale-ai/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id043
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id044
  url: /providers/sentry-system/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id045
  name: Split (Harness FME)
  slug: split
  status: profiled
  tags: *id046
  url: /providers/split/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id047
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id048
  url: /providers/splunk/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id049
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id050
  url: /providers/zoom/
siblings:
- name: Discord
  rows: 23
  url: /applications/messaging-chat/discord/
- name: Element / Matrix (Synapse)
  rows: 4
  url: /applications/messaging-chat/element-matrix-synapse/
- name: Rocket.Chat
  rows: 11
  url: /applications/messaging-chat/rocket-chat/
- name: Signal
  rows: 7
  url: /applications/messaging-chat/signal/
- name: Slack
  rows: 24
  url: /applications/messaging-chat/slack/
- name: Zulip
  rows: 11
  url: /applications/messaging-chat/zulip/
sitemap: true
title: 'Mattermost: Messaging & Team Chat reference app'
---
