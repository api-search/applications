---
app: Discourse
app_slug: discourse
app_url: https://github.com/discourse/discourse
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.40
  key: AE-170.40
  layer: domain
  name: Creator Monetisation
  providers:
  - Patreon
  url: /capabilities/creator-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: domain
  name: Social & Federated Login
  providers:
  - Discord
  - Facebook
  - GitHub
  - Google sign-in
  - LinkedIn
  - Login with Amazon
  - Microsoft
  - Sign in with Apple
  - Twitter / X
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: domain
  name: Team Chat Bridging
  providers:
  - Gitter
  - Google Chat
  - GroupMe
  - Guilded
  - Matrix
  - Mattermost
  - Microsoft Teams
  - Rocket.Chat
  - Slack
  - Telegram
  - Webex
  - Zulip
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
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
- attribution: API Evangelist extension
  id: AE-120.50.10
  key: AE-120.50.10
  layer: common
  name: IP Geolocation
  providers:
  - MaxMind
  url: /capabilities/device-ip-location/
  via_parent: Device & IP Location
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon SNS
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4250
  key: subscription-billing-revenue-management
  layer: common
  name: Subscription Billing & Revenue Management
  providers:
  - Stripe
  url: /capabilities/subscription-billing-revenue-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.10.10
  key: AE-170.10.10
  layer: common
  name: Video Hosting & Encoding
  providers:
  - AWS Elemental MediaConvert
  url: /capabilities/video-platforms/
  via_parent: Video Platforms
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Microsoft Power Automate
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Amazon Bedrock
  - Anthropic
  - Cohere
  - Google Gemini
  - Google Vertex AI
  - Hugging Face
  - Mistral AI
  - OpenAI
  - SambaNova
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: agent
  name: Model Routing & Gateways
  providers:
  - OpenRouter
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
- attribution: API Evangelist extension
  id: AE-110.10.20
  key: AE-110.10.20
  layer: agent
  name: OpenAI-Compatible Endpoints
  providers:
  - vLLM
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: community-forums
  name: Community & Forums
  url: /applications/community-forums/
counts:
  declared: 0
  observed: 44
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
- route: source code
  url: https://github.com/discourse/discourse/tree/main/lib/auth
- route: source code
  url: https://github.com/discourse/discourse/tree/main/plugins
- route: source code
  url: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
- route: source code
  url: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
- route: source code
  url: https://raw.githubusercontent.com/discourse/discourse/main/plugins/discourse-captcha/plugin.rb
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
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
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
    agent_band: agent-ready
    agent_readiness: 41.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id005
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-sns
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Email
    - Messaging
    - Notification
    url: /providers/amazon-sns/
  layer: common
  name: Amazon SNS
  provider: amazon-sns
  says: ships the Amazon SNS SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
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
    mcp: &id007
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id008
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    agent_band: agent-native
    agent_readiness: 41.4
    band: exemplar
    in_catalog: true
    kin_score: 69.3
    mcp: &id009
      status: none
    slug: amazon-mediaconvert
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Broadcasting
    - Media
    - Media Processing
    url: /providers/amazon-mediaconvert/
  layer: common
  name: AWS Elemental MediaConvert
  provider: amazon-mediaconvert
  says: ships the AWS Elemental MediaConvert SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
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
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    agent_readiness: 33.1
    band: developing
    in_catalog: true
    kin_score: 48.0
    mcp: &id013
      status: none
    slug: discord
    status: profiled
    tags: &id014
    - Chat
    - Communications
    - Discord
    - Gaming
    url: /providers/discord/
  layer: domain
  name: Discord
  provider: discord
  says: ships the Discord SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/lib/auth
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
    mcp: &id015
      status: none
    slug: facebook
    status: profiled
    tags: &id016
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/lib/auth
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
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
  layer: domain
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/lib/auth
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 3.8
    mcp: &id019
      status: none
    slug: gitter
    status: profiled
    tags: &id020
    - Development
    - Public APIs
    url: /providers/gitter/
  layer: domain
  name: Gitter
  provider: gitter
  says: ships the Gitter SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
  tier: observed
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
    agent_readiness: 41.0
    band: exemplar
    in_catalog: true
    kin_score: 67.1
    mcp: &id021
      source: https://github.com/google/mcp
      status: verified
    slug: google-chat
    status: profiled
    tags: &id022
    - Chat
    - Collaboration
    - Google
    - Google Workspace
    url: /providers/google-chat/
  layer: domain
  name: Google Chat
  provider: google-chat
  says: ships the Google Chat SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    mcp: &id023
      status: none
    slug: google-gemini
    status: profiled
    tags: &id024
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id025
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id026
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/plugins/discourse-captcha/plugin.rb
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
    mcp: &id027
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id028
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/lib/auth
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
    mcp: &id029
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: google-vertex-ai
    status: profiled
    tags: &id030
    - Artificial Intelligence
    - Generative AI
    - Google Cloud
    - Machine Learning
    url: /providers/google-vertex-ai/
  layer: agent
  name: Google Vertex AI
  provider: google-vertex-ai
  says: ships the Google Vertex AI SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id031
      status: none
    slug: groupme
    status: profiled
    tags: &id032
    - Chat
    - Company
    - Consumer
    - Messaging
    url: /providers/groupme/
  layer: domain
  name: GroupMe
  provider: groupme
  says: ships the GroupMe SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.2
    band: minimal
    in_catalog: true
    kin_score: 10.2
    mcp: &id033
      status: unknown
    slug: guilded
    status: profiled
    tags: &id034
    - Chat
    - Communications
    - Community
    - Gaming
    url: /providers/guilded/
  layer: domain
  name: Guilded
  provider: guilded
  says: ships the Guilded SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
    mcp: &id035
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id036
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/plugins/discourse-captcha/plugin.rb
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
    agent_readiness: 36.9
    band: exemplar
    in_catalog: true
    kin_score: 69.1
    mcp: &id037
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id038
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
  layer: agent
  name: Hugging Face
  provider: hugging-face
  says: ships the Hugging Face SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    mcp: &id039
      status: none
    slug: linkedin
    status: profiled
    tags: &id040
    - Business
    - Careers
    - LinkedIn
    - Marketing
    url: /providers/linkedin/
  layer: domain
  name: LinkedIn
  provider: linkedin
  says: ships the LinkedIn SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/lib/auth
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
    agent_readiness: 53.6
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id041
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id042
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Login with Amazon
  provider: amazon
  says: ships the Login with Amazon SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id043
      status: none
    slug: matrix
    status: profiled
    tags: &id044
    - Decentralized
    - Federated
    - Messaging
    - Open Standard
    url: /providers/matrix/
  layer: domain
  name: Matrix
  provider: matrix
  says: ships the Matrix SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id045
      source: https://github.com/mattermost/mmctl-mcp
      status: verified
    slug: mattermost
    status: profiled
    tags: &id046
    - Collaboration
    - Messaging
    - Open Source
    - Team Chat
    url: /providers/mattermost/
  layer: domain
  name: Mattermost
  provider: mattermost
  says: ships the Mattermost SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id047
      status: none
    slug: maxmind
    status: profiled
    tags: &id048
    - Fraud Prevention
    - Geolocation
    - IP Intelligence
    - Risk Scoring
    url: /providers/maxmind/
  layer: common
  name: MaxMind
  provider: maxmind
  says: ships the MaxMind SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
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
    mcp: &id049
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id050
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft
  provider: microsoft-entra
  says: ships the Microsoft SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins
  tier: observed
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
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id051
      status: none
    slug: microsoft-power-automate
    status: profiled
    tags: &id052
    - Automation
    - Business Process
    - Integration
    - Low-Code
    url: /providers/microsoft-power-automate/
  layer: common
  name: Microsoft Power Automate
  provider: microsoft-power-automate
  says: ships the Microsoft Power Automate SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
  tier: observed
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id053
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id054
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: domain
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    mcp: &id055
      status: none
    slug: mistral
    status: profiled
    tags: &id056
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: agent
  name: Mistral AI
  provider: mistral
  says: ships the Mistral AI SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    mcp: &id057
      status: none
    slug: ollama
    status: profiled
    tags: &id058
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    mcp: &id059
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id060
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id061
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id062
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: agent
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.40
    key: AE-170.40
    name: Creator Monetisation
    url: /capabilities/creator-monetisation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id063
      status: none
    slug: patreon
    status: profiled
    tags: &id064
    - Content
    - Creator Economy
    - Membership
    - Subscription
    url: /providers/patreon/
  layer: domain
  name: Patreon
  provider: patreon
  says: ships the Patreon SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins
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
    agent_band: agent-ready
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id065
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id066
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.9
    mcp: &id067
      source: https://docs.rocket.chat/docs/mcp-server
      status: verified
    slug: rocketchat
    status: profiled
    tags: &id068
    - Collaboration
    - Communications
    - Company
    - Open Source
    url: /providers/rocketchat/
  layer: domain
  name: Rocket.Chat
  provider: rocketchat
  says: ships the Rocket.Chat SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    agent_readiness: 28.8
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id069
      status: none
    slug: sambanova-systems
    status: profiled
    tags: &id070
    - Artificial Intelligence
    - Company
    - LLM
    - Machine Learning
    url: /providers/sambanova-systems/
  layer: agent
  name: SambaNova
  provider: sambanova-systems
  says: ships the SambaNova SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id071
      status: none
    slug: apple
    status: profiled
    tags: &id072
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: domain
  name: Sign in with Apple
  provider: apple
  says: ships the Sign in with Apple SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins
  tier: observed
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
    mcp: &id073
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id074
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id075
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id076
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id077
      status: none
    slug: telegram
    status: profiled
    tags: &id078
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
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
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id079
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id080
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter / X
  provider: x
  says: ships the Twitter / X SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/lib/auth
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.20
    key: AE-110.10.20
    name: OpenAI-Compatible Endpoints
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: emerging
    in_catalog: true
    kin_score: 25.2
    mcp: &id081
      status: none
    slug: vllm
    status: profiled
    tags: &id082
    - GPU
    - Inference
    - LLM
    - Open Source
    url: /providers/vllm/
  layer: agent
  name: vLLM
  provider: vllm
  says: ships the vLLM SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
  tier: observed
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
    agent_readiness: 61.8
    band: strong
    in_catalog: true
    kin_score: 66.1
    mcp: &id083
      source: https://github.com/WebexSamples/webex-messaging-mcp-server
      status: verified
    slug: webex
    status: profiled
    tags: &id084
    - Calling
    - Collaboration
    - Communications
    - Enterprise
    url: /providers/webex/
  layer: domain
  name: Webex
  provider: webex
  says: ships the Webex SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
  tier: observed
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
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id085
      status: none
    slug: zendesk
    status: profiled
    tags: &id086
    - CRM
    - Chat
    - Help Center
    - Sell
    url: /providers/zendesk/
  layer: common
  name: Zendesk
  provider: zendesk
  says: ships the Zendesk SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.1
    band: thin
    in_catalog: true
    kin_score: 33.1
    mcp: &id087
      source: https://github.com/zulip/zulipmcp
      status: verified
    slug: zulip
    status: profiled
    tags: &id088
    - Collaboration
    - Messaging
    - Team Chat
    - Webhook
    url: /providers/zulip/
  layer: domain
  name: Zulip
  provider: zulip
  says: ships the Zulip SDK or integration code
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/community-forums/discourse/
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
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id005
  name: Amazon SNS
  slug: amazon-sns
  status: profiled
  tags: *id006
  url: /providers/amazon-sns/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id007
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id008
  url: /providers/anthropic/
- agent_band: agent-native
  agent_readiness: 41.4
  band: exemplar
  in_catalog: true
  kin_score: 69.3
  mcp: *id009
  name: AWS Elemental MediaConvert
  slug: amazon-mediaconvert
  status: profiled
  tags: *id010
  url: /providers/amazon-mediaconvert/
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
  agent_readiness: 33.1
  band: developing
  in_catalog: true
  kin_score: 48.0
  mcp: *id013
  name: Discord
  slug: discord
  status: profiled
  tags: *id014
  url: /providers/discord/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id015
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id016
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id017
  name: GitHub
  slug: github
  status: profiled
  tags: *id018
  url: /providers/github/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 3.8
  mcp: *id019
  name: Gitter
  slug: gitter
  status: profiled
  tags: *id020
  url: /providers/gitter/
- agent_band: agent-ready
  agent_readiness: 41.0
  band: exemplar
  in_catalog: true
  kin_score: 67.1
  mcp: *id021
  name: Google Chat
  slug: google-chat
  status: profiled
  tags: *id022
  url: /providers/google-chat/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id023
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id024
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id025
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id026
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id027
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id028
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 42.2
  band: strong
  in_catalog: true
  kin_score: 63.2
  mcp: *id029
  name: Google Vertex AI
  slug: google-vertex-ai
  status: profiled
  tags: *id030
  url: /providers/google-vertex-ai/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id031
  name: GroupMe
  slug: groupme
  status: profiled
  tags: *id032
  url: /providers/groupme/
- agent_band: human-only
  agent_readiness: 3.2
  band: minimal
  in_catalog: true
  kin_score: 10.2
  mcp: *id033
  name: Guilded
  slug: guilded
  status: profiled
  tags: *id034
  url: /providers/guilded/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id035
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id036
  url: /providers/hcaptcha/
- agent_band: agent-ready
  agent_readiness: 36.9
  band: exemplar
  in_catalog: true
  kin_score: 69.1
  mcp: *id037
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id038
  url: /providers/hugging-face/
- agent_band: agent-ready
  agent_readiness: 46.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id039
  name: LinkedIn
  slug: linkedin
  status: profiled
  tags: *id040
  url: /providers/linkedin/
- agent_band: agent-native
  agent_readiness: 53.6
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id041
  name: Login with Amazon
  slug: amazon
  status: profiled
  tags: *id042
  url: /providers/amazon/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id043
  name: Matrix
  slug: matrix
  status: profiled
  tags: *id044
  url: /providers/matrix/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id045
  name: Mattermost
  slug: mattermost
  status: profiled
  tags: *id046
  url: /providers/mattermost/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id047
  name: MaxMind
  slug: maxmind
  status: profiled
  tags: *id048
  url: /providers/maxmind/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id049
  name: Microsoft
  slug: microsoft-entra
  status: profiled
  tags: *id050
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id051
  name: Microsoft Power Automate
  slug: microsoft-power-automate
  status: profiled
  tags: *id052
  url: /providers/microsoft-power-automate/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id053
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id054
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id055
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id056
  url: /providers/mistral/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id057
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id058
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id059
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id060
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id061
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id062
  url: /providers/openrouter/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id063
  name: Patreon
  slug: patreon
  status: profiled
  tags: *id064
  url: /providers/patreon/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id065
  name: Redis
  slug: redis
  status: profiled
  tags: *id066
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.9
  mcp: *id067
  name: Rocket.Chat
  slug: rocketchat
  status: profiled
  tags: *id068
  url: /providers/rocketchat/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id069
  name: SambaNova
  slug: sambanova-systems
  status: profiled
  tags: *id070
  url: /providers/sambanova-systems/
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id071
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id072
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id073
  name: Slack
  slug: slack
  status: profiled
  tags: *id074
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id075
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id076
  url: /providers/stripe/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id077
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id078
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id079
  name: Twitter / X
  slug: x
  status: profiled
  tags: *id080
  url: /providers/x/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: emerging
  in_catalog: true
  kin_score: 25.2
  mcp: *id081
  name: vLLM
  slug: vllm
  status: profiled
  tags: *id082
  url: /providers/vllm/
- agent_band: agent-ready
  agent_readiness: 61.8
  band: strong
  in_catalog: true
  kin_score: 66.1
  mcp: *id083
  name: Webex
  slug: webex
  status: profiled
  tags: *id084
  url: /providers/webex/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id085
  name: Zendesk
  slug: zendesk
  status: profiled
  tags: *id086
  url: /providers/zendesk/
- agent_band: agent-aware
  agent_readiness: 25.1
  band: thin
  in_catalog: true
  kin_score: 33.1
  mcp: *id087
  name: Zulip
  slug: zulip
  status: profiled
  tags: *id088
  url: /providers/zulip/
siblings:
- name: Circle
  rows: 36
  url: /applications/community-forums/circle/
- name: Flarum
  rows: 4
  url: /applications/community-forums/flarum/
- name: Lemmy
  rows: 2
  url: /applications/community-forums/lemmy/
- name: Mastodon
  rows: 10
  url: /applications/community-forums/mastodon/
- name: NodeBB
  rows: 9
  url: /applications/community-forums/nodebb/
sitemap: true
title: 'Discourse: Community & Forums reference app'
---
