---
access: understanding
agent_layer:
- app: Discourse
  finding: first-party MCP server (discourse/discourse-mcp); discourse-ai plugin brings BYO-LLM across 14 endpoint types
  source: https://github.com/discourse/discourse-mcp
  tier: declared
- app: Discourse
  finding: 'BYO-LLM: discourse-ai completion endpoints for Anthropic, OpenAI, Bedrock, Gemini, Vertex, Cohere, Mistral, OpenRouter, Ollama, vLLM, Hugging Face, SambaNova'
  source: https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
  tier: observed
apps:
- anchor: discourse
  counts:
    declared: 0
    observed: 44
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
    layer: domain
    name: Zulip
    provider: zulip
    says: ships the Zulip SDK or integration code
    source: https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
    tier: observed
  kind: self-hosted
  name: Discourse
  page: /applications/community-forums/discourse/
  slug: discourse
  url: https://github.com/discourse/discourse
- anchor: nodebb
  counts:
    declared: 0
    observed: 9
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
  - route: source code
    url: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: domain
    name: Akismet
    provider: akismet
    says: ships the Akismet SDK or integration code
    source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Cloudflare Turnstile
    provider: cloudflare-turnstile
    says: ships the Cloudflare Turnstile SDK or integration code
    source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: Google reCAPTCHA
    provider: google-recaptcha
    says: ships the Google reCAPTCHA SDK or integration code
    source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: MongoDB
    provider: mongodb
    says: ships the MongoDB SDK or integration code
    source: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: domain
    name: Project Honey Pot
    provider: project-honeypot
    says: ships the Project Honey Pot SDK or integration code
    source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: domain
    name: StopForumSpam
    provider: stopforumspam
    says: ships the StopForumSpam SDK or integration code
    source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
    tier: observed
  kind: self-hosted
  name: NodeBB
  page: /applications/community-forums/nodebb/
  slug: nodebb
  url: https://github.com/NodeBB/NodeBB
- anchor: flarum
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: source code
    url: https://github.com/flarum/framework/tree/main/extensions
  - route: source code
    url: https://github.com/flarum/framework/tree/main/framework/core/src/Mail
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: domain
    name: Akismet
    provider: akismet
    says: ships the Akismet SDK or integration code
    source: https://github.com/flarum/framework/tree/main/extensions
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailgun
    provider: mailgun
    says: ships the Mailgun SDK or integration code
    source: https://github.com/flarum/framework/tree/main/framework/core/src/Mail
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Postmark
    provider: postmark
    says: ships the Postmark SDK or integration code
    source: https://github.com/flarum/framework/tree/main/framework/core/src/Mail
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    credit: null
    layer: common
    name: Pusher
    provider: pusher
    says: ships the Pusher SDK or integration code
    source: https://github.com/flarum/framework/tree/main/extensions
    tier: observed
  kind: self-hosted
  name: Flarum
  page: /applications/community-forums/flarum/
  slug: flarum
  url: https://github.com/flarum/framework
- anchor: lemmy
  counts:
    declared: 0
    observed: 2
  evidence:
  - route: source code
    url: https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    credit: null
    layer: common
    name: pict-rs
    provider: pict-rs
    says: ships the pict-rs SDK or integration code
    source: https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
    tier: observed
  kind: self-hosted
  name: Lemmy
  page: /applications/community-forums/lemmy/
  slug: lemmy
  url: https://github.com/LemmyNet/lemmy
- anchor: mastodon
  counts:
    declared: 0
    observed: 10
  evidence:
  - route: dependency manifest
    url: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
  - route: source code
    url: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
  - route: source code
    url: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: DeepL
    provider: deepl
    says: ships the DeepL SDK or integration code
    source: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    credit: null
    layer: common
    name: Elasticsearch
    provider: elasticsearch
    says: ships the Elasticsearch SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    credit: null
    layer: common
    name: hCaptcha
    provider: hcaptcha
    says: ships the hCaptcha SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: LibreTranslate
    provider: libre-translate
    says: ships the LibreTranslate SDK or integration code
    source: https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: OpenStack Swift
    provider: openstack
    says: ships the OpenStack Swift SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: common
    name: OpenTelemetry
    provider: opentelemetry
    says: ships the OpenTelemetry SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: PostgreSQL
    provider: postgresql
    says: ships the PostgreSQL SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Redis
    provider: redis
    says: ships the Redis SDK or integration code
    source: https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
    tier: observed
  kind: self-hosted
  name: Mastodon
  page: /applications/community-forums/mastodon/
  slug: mastodon
  url: https://github.com/mastodon/mastodon
- anchor: circle
  counts:
    declared: 36
    observed: 0
  evidence:
  - route: integrations page
    url: https://circle.so/integrations
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Airtable
    provider: airtable
    says: lists Airtable as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: common
    name: Auth0
    provider: auth0
    says: lists Auth0 as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-931
      key: AE-931
      name: No-Code App Builders
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    credit: null
    layer: common
    name: Bubble
    provider: bubble
    says: lists Bubble as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: ConvertKit (Kit)
    provider: convertkit
    says: lists ConvertKit (Kit) as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: common
    name: Facebook / Meta Pixel
    provider: facebook
    says: lists Facebook / Meta Pixel as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics
    provider: google-analytics
    says: lists Google Analytics as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Sheets
    provider: google-sheets
    says: lists Google Sheets as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    credit: null
    layer: common
    name: Google Tag Manager
    provider: google-tag-manager
    says: lists Google Tag Manager as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Instagram
    provider: instagram
    says: lists Instagram as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-220.10
      key: AE-220.10
      name: Online Courses
      url: /capabilities/online-courses/
      via_parent: null
    credit: null
    layer: domain
    name: Kajabi
    provider: kajabi
    says: lists Kajabi as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Loom
    provider: loom
    says: lists Loom as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Make
    provider: make
    says: lists Make as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: domain
    name: Memberful
    provider: memberful
    says: lists Memberful as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: domain
    name: MemberSpace
    provider: memberspace
    says: lists MemberSpace as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: domain
    name: Memberstack
    provider: memberstack
    says: lists Memberstack as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    credit: null
    layer: domain
    name: Outseta
    provider: outseta
    says: lists Outseta as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: PayPal
    provider: paypal
    says: lists PayPal as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-3740.60
      key: syndication-affiliate-distribution
      name: Syndication & Affiliate Distribution
      url: /capabilities/syndication-affiliate-distribution/
      via_parent: null
    credit: null
    layer: common
    name: Rewardful
    provider: rewardful
    says: lists Rewardful as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: common
    name: Salesforce
    provider: salesforce
    says: lists Salesforce as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Simplecast
    provider: simplecast
    says: lists Simplecast as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    credit: null
    layer: domain
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: SoundCloud
    provider: soundcloud
    says: lists SoundCloud as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Spotify
    provider: spotify
    says: lists Spotify as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe
    provider: stripe
    says: lists Stripe as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-220.10
      key: AE-220.10
      name: Online Courses
      url: /capabilities/online-courses/
      via_parent: null
    credit: null
    layer: domain
    name: Teachable
    provider: teachable
    says: lists Teachable as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    credit: null
    layer: common
    name: ThriveCart
    provider: thrivecart
    says: lists ThriveCart as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Twitter / X
    provider: x
    says: lists Twitter / X as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    credit: null
    layer: common
    name: Typeform
    provider: typeform
    says: lists Typeform as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: Wistia
    provider: wistia
    says: lists Wistia as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: common
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    credit: null
    layer: domain
    name: YouTube
    provider: youtube
    says: lists YouTube as an integration
    source: https://circle.so/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    credit: null
    layer: common
    name: Zapier
    provider: zapier
    says: lists Zapier as an integration
    source: https://circle.so/integrations
    tier: declared
  kind: commercial
  name: Circle
  page: /applications/community-forums/circle/
  slug: circle
  url: https://circle.so/
author: API Evangelist
candidates: []
credits: []
html: public
id: community-forums
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Social Networking
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Social
  store: google-play
  url: https://play.google.com/store/apps/category/SOCIAL
- category: Communication - Social Networks and Forums
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#communication---social-networks-and-forums
- category: Communication
  store: slack-marketplace
  url: https://slack.com/apps
name: Community & Forums
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-170.50.10
    key: AE-170.50.10
    name: Online Communities
    url: /capabilities/social-networks-community/
    via_parent: Social Networks & Community
  fit: exact
  layer: domain
  why: 'what the category is: the forum/community platform itself'
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: uploads, media, backups
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: mobile push
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: common
  why: uploaded video transcoding
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: login anomaly / location
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: primary store, cache, queues
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: domain
  why: members sign in with existing accounts
- capability:
    attribution: API Evangelist extension
    id: AE-170.40
    key: AE-170.40
    name: Creator Monetisation
    url: /capabilities/creator-monetisation/
    via_parent: null
  fit: exact
  layer: domain
  why: patron-gated community access
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: support tickets from topics
- capability:
    attribution: Turbo EA
    id: BC-4250
    key: subscription-billing-revenue-management
    name: Subscription Billing & Revenue Management
    url: /capabilities/subscription-billing-revenue-management/
    via_parent: null
  fit: exact
  layer: common
  why: paid memberships
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  fit: exact
  layer: domain
  why: forums push topics/posts into team chat
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code automation
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: AI summaries, search, bots
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM routing
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: self-hosted local models
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.20
    key: AE-110.10.20
    name: OpenAI-Compatible Endpoints
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: self-hosted OpenAI-compatible serving
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  fit: exact
  layer: domain
  why: open sign-up forums fight spam registrations and posts
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  fit: exact
  layer: common
  why: live updates
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: notifications and digests
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  fit: exact
  layer: common
  why: image hosting/resizing
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: federated/multilingual posts translated inline
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: tracing/metrics export
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: member lists synced to ESPs
- capability:
    attribution: API Evangelist extension
    id: AE-922
    key: AE-922
    name: Spreadsheets & No-Code Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: member data export
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: common
  why: enterprise SSO
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: ad pixels
- capability:
    attribution: API Evangelist extension
    id: AE-170.70.10
    key: AE-170.70.10
    name: Link Unfurling & Rich Embeds
    url: /capabilities/content-management/
    via_parent: Content Management
  fit: exact
  layer: domain
  why: media embeds inside posts
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: analytics
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: site tags
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: member CRM sync
- capability:
    attribution: API Evangelist extension
    id: AE-220.10
    key: AE-220.10
    name: Online Courses
    url: /capabilities/online-courses/
    via_parent: null
  fit: exact
  layer: domain
  why: community + course bundles
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: paid communities
- capability:
    attribution: Turbo EA
    id: BC-3750.20
    key: subscription-entitlement-management
    name: Subscription & Entitlement Management
    url: /capabilities/subscription-entitlement-management/
    via_parent: null
  fit: exact
  layer: domain
  why: paid-community access gating
- capability:
    attribution: Turbo EA
    id: BC-3740.60
    key: syndication-affiliate-distribution
    name: Syndication & Affiliate Distribution
    url: /capabilities/syndication-affiliate-distribution/
    via_parent: null
  fit: exact
  layer: common
  why: affiliate programmes
- capability:
    attribution: API Evangelist extension
    id: AE-921
    key: AE-921
    name: Online Forms & Survey Collection
    url: /capabilities/customer-feedback-management/
    via_parent: Customer Feedback Management
  fit: exact
  layer: common
  why: onboarding forms
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: common
  why: CMS connection
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.40.10
      key: AE-150.40.10
      name: Team Chat Bridging
      url: /capabilities/in-app-chat/
      via_parent: In-App Chat
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Circle
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://circle.so/integrations
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
    - agent_band: agent-ready
      agent_readiness: 41.0
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Chat
      slug: google-chat
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Google
      - Google Workspace
      tier: observed
      url: /providers/google-chat/
    - agent_band: agent-ready
      agent_readiness: 61.8
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 66.1
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: observed
      url: /providers/webex/
    - agent_band: agent-ready
      agent_readiness: 30.5
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: observed
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 37.0
      mcp:
        source: https://github.com/mattermost/mmctl-mcp
        status: verified
      name: Mattermost
      slug: mattermost
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Open Source
      - Team Chat
      tier: observed
      url: /providers/mattermost/
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        source: https://github.com/zulip/zulipmcp
        status: verified
      name: Zulip
      slug: zulip
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Collaboration
      - Messaging
      - Team Chat
      - Webhook
      tier: observed
      url: /providers/zulip/
    - agent_band: agent-aware
      agent_readiness: 25.4
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 32.9
      mcp:
        status: none
      name: GroupMe
      slug: groupme
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Chat
      - Company
      - Consumer
      - Messaging
      tier: observed
      url: /providers/groupme/
    - agent_band: agent-aware
      agent_readiness: 19.7
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 30.5
      mcp:
        status: none
      name: Matrix
      slug: matrix
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Decentralized
      - Federated
      - Messaging
      - Open Standard
      tier: observed
      url: /providers/matrix/
    - agent_band: human-only
      agent_readiness: 3.2
      apps:
      - Discourse
      band: minimal
      in_catalog: true
      kin_score: 10.2
      mcp:
        status: unknown
      name: Guilded
      slug: guilded
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Chat
      - Communications
      - Community
      - Gaming
      tier: observed
      url: /providers/guilded/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Discourse
      band: minimal
      in_catalog: true
      kin_score: 3.8
      mcp:
        status: none
      name: Gitter
      slug: gitter
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Development
      - Public APIs
      tier: observed
      url: /providers/gitter/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Discourse
      band: minimal
      in_catalog: true
      kin_score: 2.9
      mcp:
        source: https://docs.rocket.chat/docs/mcp-server
        status: verified
      name: Rocket.Chat
      slug: rocketchat
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Collaboration
      - Communications
      - Company
      - Open Source
      tier: observed
      url: /providers/rocketchat/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70.10
      key: AE-170.70.10
      name: Link Unfurling & Rich Embeds
      url: /capabilities/content-management/
      via_parent: Content Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 75.5
      mcp:
        source: https://docs.wistia.com/docs/mcp-server-guide
        status: documented
      name: Wistia
      slug: wistia
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Lead Generation
      - Video Analytics
      - Video Hosting
      - Video Marketing
      tier: declared
      url: /providers/wistia/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp: &id001
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: Twitter / X
      slug: x
      sources:
      - https://circle.so/integrations
      status: profiled
      tags: &id002
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 38.6
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 67.8
      mcp:
        status: none
      name: Instagram
      slug: instagram
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Instagram
      - Meta
      - Photos
      - Social Media
      tier: declared
      url: /providers/instagram/
    - agent_band: agent-ready
      agent_readiness: 41.4
      apps:
      - Circle
      band: strong
      in_catalog: true
      kin_score: 65.4
      mcp:
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Google
      - Media
      - Video
      - YouTube
      tier: declared
      url: /providers/youtube/
    - agent_band: agent-ready
      agent_readiness: 32.7
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 50.6
      mcp:
        status: none
      name: Spotify
      slug: spotify
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Audio
      - Music
      - Podcasts
      - Streaming
      tier: declared
      url: /providers/spotify/
    - agent_band: agent-ready
      agent_readiness: 47.8
      apps:
      - Circle
      band: thin
      in_catalog: true
      kin_score: 37.6
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: declared
      url: /providers/vimeo/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Circle
      band: thin
      in_catalog: true
      kin_score: 30.9
      mcp:
        status: none
      name: SoundCloud
      slug: soundcloud
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Audio
      - Music
      - OAuth
      - Streaming
      tier: declared
      url: /providers/soundcloud/
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Circle
      band: emerging
      in_catalog: true
      kin_score: 25.9
      mcp:
        status: unknown
      name: Simplecast
      slug: simplecast
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Podcast Analytics
      - Podcast Distribution
      - Podcast Hosting
      - Podcasts
      tier: declared
      url: /providers/simplecast/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Circle
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: Loom
      slug: loom
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Async
      - Communications
      - Productivity
      - Video
      tier: declared
      url: /providers/loom/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/discourse/discourse/tree/main/lib/auth
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/discourse/discourse/tree/main/lib/auth
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp: *id001
      name: Twitter / X
      slug: x
      sources:
      - https://github.com/discourse/discourse/tree/main/lib/auth
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft
      slug: microsoft-entra
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/discourse/discourse/tree/main/lib/auth
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-native
      agent_readiness: 53.6
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 58.4
      mcp:
        source: https://github.com/amzn/selling-partner-agentic-toolkit
        status: verified
      name: Login with Amazon
      slug: amazon
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins
      status: profiled
      tags:
      - Advertising
      - Alexa
      - Amazon
      - E-Commerce
      tier: observed
      url: /providers/amazon/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Discourse
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-ready
      agent_readiness: 33.1
      apps:
      - Discourse
      band: developing
      in_catalog: true
      kin_score: 48.0
      mcp:
        status: none
      name: Discord
      slug: discord
      sources:
      - https://github.com/discourse/discourse/tree/main/lib/auth
      status: profiled
      tags:
      - Chat
      - Communications
      - Discord
      - Gaming
      tier: observed
      url: /providers/discord/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Discourse
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/discourse/discourse/tree/main/lib/auth
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Flarum
      - NodeBB
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Akismet
      slug: akismet
      sources:
      - https://github.com/flarum/framework/tree/main/extensions
      - https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-aware
      agent_readiness: 7.7
      apps:
      - NodeBB
      band: emerging
      in_catalog: true
      kin_score: 25.3
      mcp:
        status: unknown
      name: Project Honey Pot
      slug: project-honeypot
      sources:
      - https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
      status: profiled
      tags:
      - Anti-Spam
      - Community
      - Fraud Prevention
      - Security
      tier: observed
      url: /providers/project-honeypot/
    - agent_band: human-only
      agent_readiness: 1.1
      apps:
      - NodeBB
      band: emerging
      in_catalog: true
      kin_score: 15.2
      mcp:
        status: unknown
      name: StopForumSpam
      slug: stopforumspam
      sources:
      - https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
      status: profiled
      tags:
      - Community
      - Company
      - Security
      - Spam
      tier: observed
      url: /providers/stopforumspam/
  - capability:
      attribution: Turbo EA
      id: BC-3750.20
      key: subscription-entitlement-management
      name: Subscription & Entitlement Management
      url: /capabilities/subscription-entitlement-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.6
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 41.5
      mcp:
        source: https://developers.memberstack.com/mcp-server
        status: verified
      name: Memberstack
      slug: memberstack
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Authentication
      - Membership
      - Software-as-a-Service
      - Webflow
      tier: declared
      url: /providers/memberstack/
    - agent_band: human-only
      agent_readiness: 2.8
      apps:
      - Circle
      band: emerging
      in_catalog: true
      kin_score: 24.7
      mcp:
        status: none
      name: MemberSpace
      slug: memberspace
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Community
      - Membership
      - Payments
      - Software-as-a-Service
      tier: declared
      url: /providers/memberspace/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Circle
      band: emerging
      in_catalog: true
      kin_score: 12.6
      mcp:
        status: none
      name: Memberful
      slug: memberful
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Creators
      - Membership
      - Payments
      - Subscription
      tier: declared
      url: /providers/memberful/
    - agent_band: null
      agent_readiness: null
      apps:
      - Circle
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Outseta
      slug: outseta
      sources:
      - https://circle.so/integrations
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Mastodon
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Mastodon
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://github.com/mastodon/mastodon/tree/main/app/lib/translation_service
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: observed
      url: /providers/libre-translate/
  - capability:
      attribution: API Evangelist extension
      id: AE-220.10
      key: AE-220.10
      name: Online Courses
      url: /capabilities/online-courses/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.6
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 51.1
      mcp:
        status: none
      name: Teachable
      slug: teachable
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Course Management
      - E-Learning
      - Education
      - Online Courses
      tier: declared
      url: /providers/teachable/
    - agent_band: agent-ready
      agent_readiness: 51.9
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 40.1
      mcp:
        source: https://help.kajabi.com/en/collections/19761100-mcp
        status: documented
      name: Kajabi
      slug: kajabi
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Creator Economy
      - E-Commerce
      - Membership
      - Online Courses
      tier: declared
      url: /providers/kajabi/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.40
      key: AE-170.40
      name: Creator Monetisation
      url: /capabilities/creator-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Patreon
      slug: patreon
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins
      status: profiled
      tags:
      - Content
      - Creator Economy
      - Membership
      - Subscription
      tier: observed
      url: /providers/patreon/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.5
      apps:
      - Discourse
      - Mastodon
      - NodeBB
      band: developing
      in_catalog: true
      kin_score: 46.5
      mcp:
        source: https://github.com/redis/mcp-redis
        status: verified
      name: Redis
      slug: redis
      sources:
      - https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
      - https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
      - https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
      status: profiled
      tags:
      - Cache
      - Database
      - In-Memory
      - Key-Value Store
      tier: observed
      url: /providers/redis/
    - agent_band: human-only
      agent_readiness: 0.6
      apps:
      - Lemmy
      - Mastodon
      - NodeBB
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: none
      name: PostgreSQL
      slug: postgresql
      sources:
      - https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
      - https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
      - https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
      status: profiled
      tags:
      - Database
      - Open Source
      - Relational Database
      - SQL
      tier: observed
      url: /providers/postgresql/
    - agent_band: agent-ready
      agent_readiness: 59.1
      apps:
      - NodeBB
      band: exemplar
      in_catalog: true
      kin_score: 79.9
      mcp:
        source: https://github.com/mongodb-js/mongodb-mcp-server
        status: verified
      name: MongoDB
      slug: mongodb
      sources:
      - https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
      status: profiled
      tags:
      - Cloud Database
      - Database
      - Document Database
      - NoSQL
      tier: observed
      url: /providers/mongodb/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.5
      apps:
      - Discourse
      - Mastodon
      - NodeBB
      band: thin
      in_catalog: true
      kin_score: 31.1
      mcp:
        status: none
      name: hCaptcha
      slug: hcaptcha
      sources:
      - https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
      - https://raw.githubusercontent.com/discourse/discourse/main/plugins/discourse-captcha/plugin.rb
      - https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Privacy
      - hCaptcha
      tier: observed
      url: /providers/hcaptcha/
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Discourse
      - NodeBB
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
      - https://raw.githubusercontent.com/discourse/discourse/main/plugins/discourse-captcha/plugin.rb
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
    - agent_band: agent-aware
      agent_readiness: 24.2
      apps:
      - NodeBB
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        source: https://github.com/cloudflare/mcp
        status: verified
      name: Cloudflare Turnstile
      slug: cloudflare-turnstile
      sources:
      - https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
      status: profiled
      tags:
      - Bot Defense
      - CAPTCHA
      - Cloudflare
      - Turnstile
      tier: observed
      url: /providers/cloudflare-turnstile/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Discourse
      - Mastodon
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
      - https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Mastodon
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Mastodon
      band: thin
      in_catalog: true
      kin_score: 34.5
      mcp:
        status: none
      name: OpenStack Swift
      slug: openstack
      sources:
      - https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
      status: profiled
      tags:
      - Cloud Platform
      - Infrastructure-as-a-Service
      - Open Source
      - OpenStack
      tier: observed
      url: /providers/openstack/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 51.0
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 80.4
      mcp:
        status: none
      name: ConvertKit (Kit)
      slug: convertkit
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: &id005
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://circle.so/integrations
      status: profiled
      tags: &id006
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 69.9
      mcp:
        status: none
      name: ThriveCart
      slug: thrivecart
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Checkout
      - Company
      - Payments
      - Shopping Cart
      tier: declared
      url: /providers/thrivecart/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Circle
      band: strong
      in_catalog: true
      kin_score: 54.9
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: declared
      url: /providers/paypal/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 62.1
      mcp:
        status: none
      name: Microsoft Power Automate
      slug: microsoft-power-automate
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-chat-integration/lib/discourse_chat_integration/provider
      status: profiled
      tags:
      - Automation
      - Business Process
      - Integration
      - Low-Code
      tier: observed
      url: /providers/microsoft-power-automate/
    - agent_band: agent-ready
      agent_readiness: 66.1
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
  - capability:
      attribution: API Evangelist extension
      id: AE-922
      key: AE-922
      name: Spreadsheets & No-Code Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.3
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 68.2
      mcp:
        source: https://github.com/Airtable/airtable-mcp-cli
        status: verified
      name: Airtable
      slug: airtable
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Application
      - Collaboration
      - Data
      - Database
      tier: declared
      url: /providers/airtable/
    - agent_band: agent-ready
      agent_readiness: 30.1
      apps:
      - Circle
      band: strong
      in_catalog: true
      kin_score: 63.8
      mcp:
        status: none
      name: Google Sheets
      slug: google-sheets
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Google Workspace
      - Productivity
      - Spreadsheets
      tier: declared
      url: /providers/google-sheets/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Flarum
      band: exemplar
      in_catalog: true
      kin_score: 70.5
      mcp:
        source: https://github.com/ActiveCampaign/postmark-mcp
        status: verified
      name: Postmark
      slug: postmark
      sources:
      - https://github.com/flarum/framework/tree/main/framework/core/src/Mail
      status: profiled
      tags:
      - Deliverability
      - Email
      - Messaging
      - Transactional Email
      tier: observed
      url: /providers/postmark/
    - agent_band: agent-aware
      agent_readiness: 19.2
      apps:
      - Flarum
      band: thin
      in_catalog: true
      kin_score: 31.6
      mcp:
        source: https://github.com/mailgun/mailgun-mcp-server
        status: verified
      name: Mailgun
      slug: mailgun
      sources:
      - https://github.com/flarum/framework/tree/main/framework/core/src/Mail
      status: profiled
      tags:
      - Email
      - Email Verification
      - SMTP
      - Transactional Email
      tier: observed
      url: /providers/mailgun/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.7
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: observed
      url: /providers/zendesk/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id003
      name: Facebook / Meta Pixel
      slug: facebook
      sources:
      - https://circle.so/integrations
      status: profiled
      tags: *id004
      tier: declared
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 31.5
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
      status: profiled
      tags:
      - Fraud Prevention
      - Geolocation
      - IP Intelligence
      - Risk Scoring
      tier: observed
      url: /providers/maxmind/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.30.10
      key: AE-170.30.10
      name: Image Processing & Optimisation
      url: /capabilities/photo-image-libraries/
      via_parent: Photo & Image Libraries
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Lemmy
      band: emerging
      in_catalog: true
      kin_score: 25.4
      mcp:
        status: unknown
      name: pict-rs
      slug: pict-rs
      sources:
      - https://raw.githubusercontent.com/LemmyNet/lemmy/main/config/defaults.hjson
      status: profiled
      tags:
      - Image Hosting
      - Open Source
      - Rust
      - Self-Hosted
      tier: observed
      url: /providers/pict-rs/
  - capability:
      attribution: API Evangelist extension
      id: AE-931
      key: AE-931
      name: No-Code App Builders
      url: /capabilities/engineering-productivity-management/
      via_parent: Engineering Productivity Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 20.4
      apps:
      - Circle
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: Bubble
      slug: bubble
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Application Platform
      - Database
      - No-Code
      - Workflow Automation
      tier: declared
      url: /providers/bubble/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 27.3
      apps:
      - Mastodon
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: none
      name: OpenTelemetry
      slug: opentelemetry
      sources:
      - https://raw.githubusercontent.com/mastodon/mastodon/main/Gemfile
      status: profiled
      tags:
      - Cloud-Native
      - Logging
      - Metrics
      - Monitoring
      tier: observed
      url: /providers/opentelemetry/
  - capability:
      attribution: API Evangelist extension
      id: AE-921
      key: AE-921
      name: Online Forms & Survey Collection
      url: /capabilities/customer-feedback-management/
      via_parent: Customer Feedback Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.6
      apps:
      - Circle
      band: thin
      in_catalog: true
      kin_score: 36.0
      mcp:
        source: https://www.typeform.com/developers/mcp
        status: verified
      name: Typeform
      slug: typeform
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Forms
      - Lead Capture
      - Software-as-a-Service
      - Surveys
      tier: declared
      url: /providers/typeform/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 64.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.70
      key: AE-150.70
      name: Realtime Messaging
      url: /capabilities/realtime-messaging/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.8
      apps:
      - Flarum
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Pusher
      slug: pusher
      sources:
      - https://github.com/flarum/framework/tree/main/extensions
      status: profiled
      tags:
      - Pub/Sub
      - Push Notifications
      - Real-Time
      - WebSocket
      tier: observed
      url: /providers/pusher/
  - capability:
      attribution: Turbo EA
      id: BC-830.20.30
      key: BC-830.20.30
      name: Search and Discovery Management
      url: /capabilities/knowledge-curation-taxonomy-management/
      via_parent: Knowledge Curation & Taxonomy Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Mastodon
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        source: https://github.com/elastic/mcp-server-elasticsearch
        status: verified
      name: Elasticsearch
      slug: elasticsearch
      sources:
      - https://raw.githubusercontent.com/mastodon/mastodon/main/.env.production.sample
      status: profiled
      tags:
      - Analytics
      - Database
      - Full-Text Search
      - NoSQL
      tier: observed
      url: /providers/elasticsearch/
  - capability:
      attribution: Turbo EA
      id: BC-4250
      key: subscription-billing-revenue-management
      name: Subscription Billing & Revenue Management
      url: /capabilities/subscription-billing-revenue-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 57.6
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp: *id005
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-3740.60
      key: syndication-affiliate-distribution
      name: Syndication & Affiliate Distribution
      url: /capabilities/syndication-affiliate-distribution/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 66.7
      mcp:
        status: none
      name: Rewardful
      slug: rewardful
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Affiliate Tracking
      - Referral Programs
      - Software-as-a-Service
      - Stripe
      tier: declared
      url: /providers/rewardful/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.8
      apps:
      - Circle
      band: strong
      in_catalog: true
      kin_score: 65.8
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.5
      apps:
      - Circle
      band: exemplar
      in_catalog: true
      kin_score: 71.8
      mcp:
        source: https://auth0.com/docs/get-started/auth0-mcp-server
        status: verified
      name: Auth0
      slug: auth0
      sources:
      - https://circle.so/integrations
      status: profiled
      tags:
      - AI Agents
      - Auth0
      - Authentication
      - Authorization
      tier: declared
      url: /providers/auth0/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-native
      agent_readiness: 41.4
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 69.3
      mcp:
        status: none
      name: AWS Elemental MediaConvert
      slug: amazon-mediaconvert
      sources:
      - https://raw.githubusercontent.com/discourse/discourse/main/Gemfile
      status: profiled
      tags:
      - Amazon Web Services
      - Broadcasting
      - Media
      - Media Processing
      tier: observed
      url: /providers/amazon-mediaconvert/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Discourse
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face
      slug: hugging-face
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
    - agent_band: agent-native
      agent_readiness: 48.3
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Vertex AI
      slug: google-vertex-ai
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-ready
      agent_readiness: 28.8
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        status: none
      name: SambaNova
      slug: sambanova-systems
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - LLM
      - Machine Learning
      tier: observed
      url: /providers/sambanova-systems/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Discourse
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-ready
      agent_readiness: 40.6
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 35.2
      mcp:
        status: none
      name: Cohere
      slug: cohere
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - Natural Language Processing
      - Vector Search
      tier: observed
      url: /providers/cohere/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.4
      apps:
      - Discourse
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: observed
      url: /providers/openrouter/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Discourse
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.20
      key: AE-110.10.20
      name: OpenAI-Compatible Endpoints
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - Discourse
      band: emerging
      in_catalog: true
      kin_score: 25.2
      mcp:
        status: none
      name: vLLM
      slug: vllm
      sources:
      - https://github.com/discourse/discourse/tree/main/plugins/discourse-ai/lib/completions/endpoints
      status: profiled
      tags:
      - GPU
      - Inference
      - LLM
      - Open Source
      tier: observed
      url: /providers/vllm/
  layer: agent
summary:
  coverage_pct: 97.8
  declared_only: 33
  distinct_providers: 92
  in_catalog: 90
  mcp:
    documented: 4
    none: 43
    unchecked: 2
    verified: 38
  mcp_verified: 38
  mean_kin_score: 52.5
  observed: 59
  queued: 2
  reference_apps: 6
title: 'Community & Forums: application blueprint'
---
