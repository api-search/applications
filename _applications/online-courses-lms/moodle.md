---
app: Moodle
app_slug: moodle
app_url: https://github.com/moodle/moodle
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  - Google Drive
  - Nextcloud
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4790
  key: educational-content-learning-resource-management
  layer: domain
  name: Educational Content & Learning Resource Management
  providers:
  - Flickr
  - YouTube
  url: /capabilities/educational-content-learning-resource-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4790.30
  key: BC-4790.30
  layer: domain
  name: Open Educational Resource Management
  providers:
  - MERLOT
  - Wikimedia Commons
  url: /capabilities/educational-content-learning-resource-management/
  via_parent: Educational Content & Learning Resource Management
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: domain
  name: Video Calling
  providers:
  - BigBlueButton
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: domain
  name: Video Hosting & Encoding
  providers:
  - Vimeo
  - YouTube
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  url: /capabilities/asset-storage-tiering/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - PayPal
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Amazon SNS
  - Modica
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Clever
  - Facebook
  - Google sign-in
  - LinkedIn
  - Microsoft
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - AWS Bedrock
  - Azure AI
  - DeepSeek
  - Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: agent
  name: On-Device & Edge Inference
  providers:
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: online-courses-lms
  name: Online Courses & Learning Management
  url: /applications/online-courses-lms/
counts:
  declared: 0
  observed: 27
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.moodle.moodlemobile/latest/
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/ai/provider
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/files/converter
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/media/player
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/mod/bigbluebuttonbn
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/payment/gateway
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/repository
- route: source code
  url: https://github.com/moodle/moodle/tree/main/public/sms/gateway
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id002
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id003
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id004
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id005
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/sms/gateway
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
    mcp: &id006
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id007
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
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
    mcp: &id008
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-bedrock
    status: profiled
    tags: &id009
    - Amazon Web Services
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/amazon-bedrock/
  layer: agent
  name: AWS Bedrock
  provider: amazon-bedrock
  says: ships the AWS Bedrock SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
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
    agent_readiness: 37.8
    band: strong
    in_catalog: true
    kin_score: 66.3
    mcp: &id010
      source: https://github.com/microsoft-foundry/mcp-foundry
      status: verified
    slug: azure-ai-foundry
    status: profiled
    tags: &id011
    - AI Agents
    - Artificial Intelligence
    - Foundation Models
    - Generative AI
    url: /providers/azure-ai-foundry/
  layer: agent
  name: Azure AI
  provider: azure-ai-foundry
  says: ships the Azure AI SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
  tier: observed
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
    band: emerging
    in_catalog: true
    kin_score: 11.5
    mcp: &id012
      status: none
    slug: bigbluebutton
    status: profiled
    tags: &id013
    - Company
    - Education
    - Open Source
    - Video Conferencing
    url: /providers/bigbluebutton/
  layer: domain
  name: BigBlueButton
  provider: bigbluebutton
  says: ships the BigBlueButton SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/mod/bigbluebuttonbn
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
    agent_readiness: 31.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id014
      status: none
    slug: clever
    status: profiled
    tags: &id015
    - EdTech
    - Education
    - K-12
    - SSO
    url: /providers/clever/
  layer: common
  name: Clever
  provider: clever
  says: ships the Clever SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
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
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id016
      status: none
    slug: deepseek
    status: profiled
    tags: &id017
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: agent
  name: DeepSeek
  provider: deepseek
  says: ships the DeepSeek SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id018
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id019
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: ships the Dropbox SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id020
      status: none
    slug: facebook
    status: profiled
    tags: &id021
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4790
    key: educational-content-learning-resource-management
    name: Educational Content & Learning Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.1
    band: developing
    in_catalog: true
    kin_score: 49.1
    mcp: &id022
      status: none
    slug: flickr
    status: profiled
    tags: &id023
    - Photography
    - Photos
    - Public APIs
    - Social Media
    url: /providers/flickr/
  layer: domain
  name: Flickr
  provider: flickr
  says: ships the Flickr SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
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
    mcp: &id024
      status: none
    slug: google-gemini
    status: profiled
    tags: &id025
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Gemini
  provider: google-gemini
  says: ships the Gemini SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id026
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id027
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
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
    mcp: &id028
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id029
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
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
    agent_readiness: 46.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id030
      status: none
    slug: linkedin
    status: profiled
    tags: &id031
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: common
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4790.30
    key: BC-4790.30
    name: Open Educational Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: Educational Content & Learning Resource Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 4.1
    mcp: &id032
      status: unknown
    slug: merlot
    status: profiled
    tags: &id033
    - Community
    - Company
    - Education
    - Open Source
    url: /providers/merlot/
  layer: domain
  name: MERLOT
  provider: merlot
  says: ships the MERLOT SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
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
    mcp: &id034
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id035
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.7
    mcp: &id036
      status: unknown
    slug: modica
    status: profiled
    tags: &id037
    - CPaaS
    - Communications
    - Enterprise
    - Messaging
    url: /providers/modica/
  layer: common
  name: Modica
  provider: modica
  says: ships the Modica SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/sms/gateway
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.6
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id038
      status: none
    slug: nextcloud
    status: profiled
    tags: &id039
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud
  provider: nextcloud
  says: ships the Nextcloud SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id040
      status: none
    slug: ollama
    status: profiled
    tags: &id041
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id042
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id043
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: OneDrive
  provider: microsoft-onedrive
  says: ships the OneDrive SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
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
    mcp: &id044
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id045
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
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
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id046
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id047
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: common
  name: PayPal
  provider: paypal
  says: ships the PayPal SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/payment/gateway
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: thin
    in_catalog: true
    kin_score: 37.6
    mcp: &id048
      source: https://developer.vimeo.com/api/mcp-server
      status: documented
    slug: vimeo
    status: profiled
    tags: &id049
    - Live Streaming
    - Streaming
    - Video
    - Video Hosting
    url: /providers/vimeo/
  layer: domain
  name: Vimeo
  provider: vimeo
  says: ships the Vimeo SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/media/player
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4790.30
    key: BC-4790.30
    name: Open Educational Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: Educational Content & Learning Resource Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.0
    band: developing
    in_catalog: true
    kin_score: 49.8
    mcp: &id050
      status: none
    slug: wikimedia
    status: profiled
    tags: &id051
    - Encyclopedia
    - Open Knowledge
    - Wikimedia
    - Wikipedia
    url: /providers/wikimedia/
  layer: domain
  name: Wikimedia Commons
  provider: wikimedia
  says: ships the Wikimedia Commons SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4790
    key: educational-content-learning-resource-management
    name: Educational Content & Learning Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 41.4
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id052
      status: none
    slug: youtube
    status: profiled
    tags: &id053
    - Google
    - Media
    - Video
    - YouTube
    url: /providers/youtube/
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/repository
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  credit: null
  facts: *id001
  layer: domain
  name: YouTube
  provider: youtube
  says: ships the YouTube SDK or integration code
  source: https://github.com/moodle/moodle/tree/main/public/media/player
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/online-courses-lms/moodle/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id002
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id003
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id004
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id005
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id006
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id007
  url: /providers/anthropic/
- agent_band: agent-native
  agent_readiness: 48.3
  band: strong
  in_catalog: true
  kin_score: 64.3
  mcp: *id008
  name: AWS Bedrock
  slug: amazon-bedrock
  status: profiled
  tags: *id009
  url: /providers/amazon-bedrock/
- agent_band: agent-ready
  agent_readiness: 37.8
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id010
  name: Azure AI
  slug: azure-ai-foundry
  status: profiled
  tags: *id011
  url: /providers/azure-ai-foundry/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.5
  mcp: *id012
  name: BigBlueButton
  slug: bigbluebutton
  status: profiled
  tags: *id013
  url: /providers/bigbluebutton/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id014
  name: Clever
  slug: clever
  status: profiled
  tags: *id015
  url: /providers/clever/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id016
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id017
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id018
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id019
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id020
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id021
  url: /providers/facebook/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: developing
  in_catalog: true
  kin_score: 49.1
  mcp: *id022
  name: Flickr
  slug: flickr
  status: profiled
  tags: *id023
  url: /providers/flickr/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id024
  name: Gemini
  slug: google-gemini
  status: profiled
  tags: *id025
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id026
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id027
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id028
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id029
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id030
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id031
  url: /providers/linkedin/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 4.1
  mcp: *id032
  name: MERLOT
  slug: merlot
  status: profiled
  tags: *id033
  url: /providers/merlot/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id034
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id035
  url: /providers/microsoft-entra/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.7
  mcp: *id036
  name: Modica
  slug: modica
  status: profiled
  tags: *id037
  url: /providers/modica/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id038
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id039
  url: /providers/nextcloud/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id040
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id041
  url: /providers/ollama/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id042
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id043
  url: /providers/microsoft-onedrive/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id044
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id045
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id046
  name: PayPal
  slug: paypal
  status: profiled
  tags: *id047
  url: /providers/paypal/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: thin
  in_catalog: true
  kin_score: 37.6
  mcp: *id048
  name: Vimeo
  slug: vimeo
  status: profiled
  tags: *id049
  url: /providers/vimeo/
- agent_band: agent-ready
  agent_readiness: 32.0
  band: developing
  in_catalog: true
  kin_score: 49.8
  mcp: *id050
  name: Wikimedia Commons
  slug: wikimedia
  status: profiled
  tags: *id051
  url: /providers/wikimedia/
- agent_band: agent-ready
  agent_readiness: 41.4
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id052
  name: YouTube
  slug: youtube
  status: profiled
  tags: *id053
  url: /providers/youtube/
siblings:
- name: Canvas LMS
  rows: 25
  url: /applications/online-courses-lms/canvas-lms/
- name: Chamilo
  rows: 13
  url: /applications/online-courses-lms/chamilo/
- name: Coursera
  rows: 4
  url: /applications/online-courses-lms/coursera/
- name: LearnWorlds
  rows: 55
  url: /applications/online-courses-lms/learnworlds/
- name: Open edX
  rows: 8
  url: /applications/online-courses-lms/open-edx/
- name: Thinkific
  rows: 13
  url: /applications/online-courses-lms/thinkific/
- name: Udemy
  rows: 6
  url: /applications/online-courses-lms/udemy/
sitemap: true
title: 'Moodle: Online Courses & Learning Management reference app'
---
