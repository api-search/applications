---
app: Grafana
app_slug: grafana
app_url: https://github.com/grafana/grafana
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: domain
  name: Incident Response Management
  providers:
  - Opsgenie
  - PagerDuty
  - VictorOps
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - DingTalk
  - Discord
  - Google Chat
  - LINE
  - Microsoft Teams
  - Slack
  - Telegram
  - Threema
  - Webex
  - WeChat
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Azure Monitor data source
  - cloud.google.com/go/monitoring
  - Sensu Go
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: common
  name: Configuration & Secrets Management
  providers:
  - aws-sdk-go-v2/service/kms
  - aws-sdk-go-v2/service/secretsmanager
  - azure-sdk-for-go keyvault/azkeys
  - cloud.google.com/go/kms
  - hashicorp/vault/api
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon SNS
  - Pushover
  url: /capabilities/push-notifications/
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
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - aws-sdk-go-v2/service/s3
  - azure-sdk-for-go storage/azblob
  - cloud.google.com/go/storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - aws-sdk-go-v2/service/bedrockruntime
  - cloud.google.com/go/aiplatform
  - openai/openai-go/v3
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: observability-monitoring
  name: Observability, Monitoring & Status Pages
  url: /applications/observability-monitoring/
counts:
  declared: 0
  observed: 30
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
- route: source code
  url: https://github.com/grafana/alerting/tree/main/receivers
- route: source code
  url: https://github.com/grafana/grafana/tree/main/public/app/plugins/datasource
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 48.3
    band: strong
    in_catalog: true
    kin_score: 64.3
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: aws-sdk-go-v2/service/bedrockruntime
  provider: amazon-bedrock
  says: ships the aws-sdk-go-v2/service/bedrockruntime SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_band: agent-ready
    agent_readiness: 44.1
    band: exemplar
    in_catalog: true
    kin_score: 76.8
    mcp: &id005
      status: none
    slug: amazon-kms
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Cryptography
    - Data Protection
    - Encryption
    url: /providers/amazon-kms/
  layer: common
  name: aws-sdk-go-v2/service/kms
  provider: amazon-kms
  says: ships the aws-sdk-go-v2/service/kms SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id007
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: aws-sdk-go-v2/service/s3
  provider: amazon-s3
  says: ships the aws-sdk-go-v2/service/s3 SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_band: agent-native
    agent_readiness: 39.2
    band: exemplar
    in_catalog: true
    kin_score: 77.5
    mcp: &id009
      status: none
    slug: amazon-secrets-manager
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Configuration
    - Credentials
    - Rotation
    url: /providers/amazon-secrets-manager/
  layer: common
  name: aws-sdk-go-v2/service/secretsmanager
  provider: amazon-secrets-manager
  says: ships the aws-sdk-go-v2/service/secretsmanager SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_band: agent-aware
    agent_readiness: 26.8
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-monitor
    status: profiled
    tags: &id012
    - Application Insights
    - Cloud
    - Logs
    - Metrics
    url: /providers/microsoft-azure-monitor/
  layer: domain
  name: Azure Monitor data source
  provider: microsoft-azure-monitor
  says: ships the Azure Monitor data source SDK or integration code
  source: https://github.com/grafana/grafana/tree/main/public/app/plugins/datasource
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
    agent_band: agent-ready
    agent_readiness: 36.6
    band: strong
    in_catalog: true
    kin_score: 63.8
    mcp: &id013
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-key-vault
    status: profiled
    tags: &id014
    - Certificates
    - Cloud Security
    - Cryptography
    - Key Management
    url: /providers/microsoft-azure-key-vault/
  layer: common
  name: azure-sdk-for-go keyvault/azkeys
  provider: microsoft-azure-key-vault
  says: ships the azure-sdk-for-go keyvault/azkeys SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id016
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: azure-sdk-for-go storage/azblob
  provider: microsoft-azure-blob-storage
  says: ships the azure-sdk-for-go storage/azblob SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    mcp: &id017
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: agent
  name: cloud.google.com/go/aiplatform
  provider: google-vertex-ai
  says: ships the cloud.google.com/go/aiplatform SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 70.9
    mcp: &id019
      status: none
    slug: google-cloud-kms
    status: profiled
    tags: &id020
    - Cryptography
    - Encryption
    - Google Cloud
    - Key Management
    url: /providers/google-cloud-kms/
  layer: common
  name: cloud.google.com/go/kms
  provider: google-cloud-kms
  says: ships the cloud.google.com/go/kms SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_readiness: 37.2
    band: strong
    in_catalog: true
    kin_score: 66.4
    mcp: &id021
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-cloud-monitoring
    status: profiled
    tags: &id022
    - Alerting
    - Dashboards
    - Google Cloud
    - Metrics
    url: /providers/google-cloud-monitoring/
  layer: domain
  name: cloud.google.com/go/monitoring
  provider: google-cloud-monitoring
  says: ships the cloud.google.com/go/monitoring SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    mcp: &id023
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id024
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: cloud.google.com/go/storage
  provider: gcp-cloud-storage
  says: ships the cloud.google.com/go/storage SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.1
    mcp: &id025
      source: https://github.com/open-dingtalk/dingtalk-mcp
      status: verified
    slug: dingtalk
    status: profiled
    tags: &id026
    - Collaboration
    - Communications
    - Company
    - Enterprise
    url: /providers/dingtalk/
  layer: domain
  name: DingTalk
  provider: dingtalk
  says: ships the DingTalk SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id027
      status: none
    slug: discord
    status: profiled
    tags: &id028
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id029
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id030
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: domain
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 29.7
    mcp: &id031
      source: https://github.com/hashicorp/vault-mcp-server
      status: verified
    slug: hvault
    status: profiled
    tags: &id032
    - Encryption
    - Identity
    - Infrastructure
    - Secrets Management
    url: /providers/hvault/
  layer: common
  name: hashicorp/vault/api
  provider: hvault
  says: ships the hashicorp/vault/api SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id033
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id034
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: agent-native
    agent_readiness: 47.0
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id035
      source: https://github.com/line/line-bot-mcp-server
      status: verified
    slug: line
    status: profiled
    tags: &id036
    - Chatbots
    - Messaging
    - Mini Apps
    - Social Login
    url: /providers/line/
  layer: domain
  name: LINE
  provider: line
  says: ships the LINE SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id037
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id038
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    mcp: &id039
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id040
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: openai/openai-go/v3
  provider: openai
  says: ships the openai/openai-go/v3 SDK or integration code
  source: https://raw.githubusercontent.com/grafana/grafana/main/go.mod
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
    agent_readiness: 26.5
    band: developing
    in_catalog: true
    kin_score: 48.6
    mcp: &id041
      status: none
    slug: opsgenie
    status: profiled
    tags: &id042
    - Alerts
    - Incident Management
    - Monitoring
    - On-Call
    url: /providers/opsgenie/
  layer: domain
  name: Opsgenie
  provider: opsgenie
  says: ships the Opsgenie SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id043
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id044
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
  tier: observed
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
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 28.1
    mcp: &id045
      status: none
    slug: pushover
    status: profiled
    tags: &id046
    - Alerts
    - Messaging
    - Notification
    - Push Notifications
    url: /providers/pushover/
  layer: common
  name: Pushover
  provider: pushover
  says: ships the Pushover SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id047
      status: none
    slug: sensu
    status: profiled
    tags: &id048
    - Company
    - Infrastructure
    - Monitoring
    - Observability
    url: /providers/sensu/
  layer: domain
  name: Sensu Go
  provider: sensu
  says: ships the Sensu Go SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id051
      status: none
    slug: telegram
    status: profiled
    tags: &id052
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: human-only
    agent_readiness: 2.8
    band: thin
    in_catalog: true
    kin_score: 30.7
    mcp: &id053
      status: none
    slug: threema
    status: profiled
    tags: &id054
    - Company
    - Messaging
    - Privacy
    - Security
    url: /providers/threema/
  layer: domain
  name: Threema
  provider: threema
  says: ships the Threema SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 18.1
    mcp: &id055
      status: none
    slug: victorops
    status: profiled
    tags: &id056
    - Alerting
    - DevOps
    - Incident Management
    - On-Call
    url: /providers/victorops/
  layer: domain
  name: VictorOps
  provider: victorops
  says: ships the VictorOps SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id057
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id058
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
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
    agent_band: agent-aware
    agent_readiness: 23.6
    band: developing
    in_catalog: true
    kin_score: 45.1
    mcp: &id059
      status: none
    slug: wechat
    status: profiled
    tags: &id060
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: domain
  name: WeChat
  provider: wechat
  says: ships the WeChat SDK or integration code
  source: https://github.com/grafana/alerting/tree/main/receivers
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/observability-monitoring/grafana/
providers:
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id001
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id002
  url: /providers/amazon-sns/
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id003
  name: aws-sdk-go-v2/service/bedrockruntime
  slug: amazon-bedrock
  status: profiled
  tags: *id004
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: exemplar
  in_catalog: true
  kin_score: 76.8
  mcp: *id005
  name: aws-sdk-go-v2/service/kms
  slug: amazon-kms
  status: profiled
  tags: *id006
  url: /providers/amazon-kms/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id007
  name: aws-sdk-go-v2/service/s3
  slug: amazon-s3
  status: profiled
  tags: *id008
  url: /providers/amazon-s3/
- agent_band: agent-native
  agent_readiness: 39.2
  band: exemplar
  in_catalog: true
  kin_score: 77.5
  mcp: *id009
  name: aws-sdk-go-v2/service/secretsmanager
  slug: amazon-secrets-manager
  status: profiled
  tags: *id010
  url: /providers/amazon-secrets-manager/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id011
  name: Azure Monitor data source
  slug: microsoft-azure-monitor
  status: profiled
  tags: *id012
  url: /providers/microsoft-azure-monitor/
- agent_band: agent-ready
  agent_readiness: 36.6
  band: strong
  in_catalog: true
  kin_score: 63.8
  mcp: *id013
  name: azure-sdk-for-go keyvault/azkeys
  slug: microsoft-azure-key-vault
  status: profiled
  tags: *id014
  url: /providers/microsoft-azure-key-vault/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id015
  name: azure-sdk-for-go storage/azblob
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id016
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id017
  name: cloud.google.com/go/aiplatform
  slug: google-vertex-ai
  status: profiled
  tags: *id018
  url: /providers/google-vertex-ai/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 70.9
  mcp: *id019
  name: cloud.google.com/go/kms
  slug: google-cloud-kms
  status: profiled
  tags: *id020
  url: /providers/google-cloud-kms/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: strong
  in_catalog: true
  kin_score: 66.4
  mcp: *id021
  name: cloud.google.com/go/monitoring
  slug: google-cloud-monitoring
  status: profiled
  tags: *id022
  url: /providers/google-cloud-monitoring/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id023
  name: cloud.google.com/go/storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id024
  url: /providers/gcp-cloud-storage/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.1
  mcp: *id025
  name: DingTalk
  slug: dingtalk
  status: profiled
  tags: *id026
  url: /providers/dingtalk/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id027
  name: Discord
  slug: discord
  status: profiled
  tags: *id028
  url: /providers/discord/
- agent_band: agent-ready
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id029
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id030
  url: /providers/google-chat/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 29.7
  mcp: *id031
  name: hashicorp/vault/api
  slug: hvault
  status: profiled
  tags: *id032
  url: /providers/hvault/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id033
  name: Jira
  slug: jira
  status: profiled
  tags: *id034
  url: /providers/jira/
- agent_band: agent-native
  agent_readiness: 47.0
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id035
  name: LINE
  slug: line
  status: profiled
  tags: *id036
  url: /providers/line/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id037
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id038
  url: /providers/microsoft-teams/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id039
  name: openai/openai-go/v3
  slug: openai
  status: profiled
  tags: *id040
  url: /providers/openai/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: developing
  in_catalog: true
  kin_score: 48.6
  mcp: *id041
  name: Opsgenie
  slug: opsgenie
  status: profiled
  tags: *id042
  url: /providers/opsgenie/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id043
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id044
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 28.1
  mcp: *id045
  name: Pushover
  slug: pushover
  status: profiled
  tags: *id046
  url: /providers/pushover/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id047
  name: Sensu Go
  slug: sensu
  status: profiled
  tags: *id048
  url: /providers/sensu/
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
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id051
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id052
  url: /providers/telegram/
- agent_band: human-only
  agent_readiness: 2.8
  band: thin
  in_catalog: true
  kin_score: 30.7
  mcp: *id053
  name: Threema
  slug: threema
  status: profiled
  tags: *id054
  url: /providers/threema/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 18.1
  mcp: *id055
  name: VictorOps
  slug: victorops
  status: profiled
  tags: *id056
  url: /providers/victorops/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id057
  name: Webex
  slug: webex
  status: profiled
  tags: *id058
  url: /providers/webex/
- agent_band: agent-aware
  agent_readiness: 23.6
  band: developing
  in_catalog: true
  kin_score: 45.1
  mcp: *id059
  name: WeChat
  slug: wechat
  status: profiled
  tags: *id060
  url: /providers/wechat/
siblings:
- name: Datadog
  rows: 21
  url: /applications/observability-monitoring/datadog/
- name: Gatus
  rows: 38
  url: /applications/observability-monitoring/gatus/
- name: Netdata
  rows: 22
  url: /applications/observability-monitoring/netdata/
- name: Prometheus Alertmanager
  rows: 15
  url: /applications/observability-monitoring/prometheus-alertmanager/
- name: Sentry
  rows: 31
  url: /applications/observability-monitoring/sentry/
- name: Uptime Kuma
  rows: 50
  url: /applications/observability-monitoring/uptime-kuma/
sitemap: true
title: 'Grafana: Observability, Monitoring & Status Pages reference app'
---
