---
access: understanding
agent_layer:
- app: Moodle
  finding: core AI subsystem with BYO-LLM provider plugins (OpenAI, Anthropic, Bedrock, Azure AI, Gemini, DeepSeek, Ollama)
  source: https://github.com/moodle/moodle/tree/main/public/ai/provider
  tier: observed
- app: Chamilo
  finding: 'symfony/mcp-bundle in composer.json: the app ships its own MCP server bundle'
  source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  tier: observed
- app: Canvas LMS
  finding: 'aws-sdk-bedrockruntime + inst_llm gems: LLM features run on Amazon Bedrock'
  source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  tier: observed
apps:
- anchor: moodle
  counts:
    declared: 0
    observed: 27
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
    layer: domain
    name: YouTube
    provider: youtube
    says: ships the YouTube SDK or integration code
    source: https://github.com/moodle/moodle/tree/main/public/media/player
    tier: observed
  kind: self-hosted
  name: Moodle
  page: /applications/online-courses-lms/moodle/
  slug: moodle
  url: https://github.com/moodle/moodle
- anchor: canvas-lms
  counts:
    declared: 0
    observed: 25
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
  - route: dependency manifest
    url: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
  - route: source code
    url: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4700.30
      key: curriculum-mapping-alignment
      name: Curriculum Mapping & Alignment
      url: /capabilities/curriculum-mapping-alignment/
      via_parent: null
    credit: null
    layer: domain
    name: Academic Benchmarks
    provider: academic-benchmarks
    says: ships the Academic Benchmarks SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Connect
    provider: adobe-connect
    says: ships the Adobe Connect SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
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
    name: Amazon Bedrock
    provider: amazon-bedrock
    says: ships the Amazon Bedrock SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
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
    name: Amazon DynamoDB
    provider: amazon-dynamodb
    says: ships the Amazon DynamoDB SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Amazon Kinesis
    provider: kinesis
    says: ships the Amazon Kinesis SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Amazon S3
    provider: amazon-s3
    says: ships the Amazon S3 SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
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
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: common
    name: Amazon SQS
    provider: amazon-sqs
    says: ships the Amazon SQS SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Clever
    provider: clever
    says: ships the Clever SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
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
    name: Datadog
    provider: datadog
    says: ships the Datadog SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    credit: null
    layer: domain
    name: Diigo
    provider: diigo
    says: ships the Diigo SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google
    provider: google-identity-platform
    says: ships the Google SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google CrashLytics
    provider: firebase
    says: ships the Google CrashLytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Drive
    provider: google-drive
    says: ships the Google Drive SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Kaltura
    provider: kaltura
    says: ships the Kaltura SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: LinkedIn
    provider: linkedin
    says: ships the LinkedIn SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Microsoft
    provider: microsoft-entra
    says: ships the Microsoft SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Pendo
    provider: pendoio
    says: ships the Pendo SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
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
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Sign in with Apple
    provider: apple
    says: ships the Sign in with Apple SDK or integration code
    source: https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4740.60.10
      key: BC-4740.60.10
      name: Plagiarism Detection
      url: /capabilities/academic-integrity-management/
      via_parent: Academic Integrity Management
    credit: null
    layer: domain
    name: Turnitin
    provider: turnitin
    says: ships the Turnitin SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4740.60.10
      key: BC-4740.60.10
      name: Plagiarism Detection
      url: /capabilities/academic-integrity-management/
      via_parent: Academic Integrity Management
    credit: null
    layer: domain
    name: VeriCite
    provider: vericite
    says: ships the VeriCite SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Webex
    provider: webex
    says: ships the Webex SDK or integration code
    source: https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
    tier: observed
  kind: self-hosted
  name: Canvas LMS
  page: /applications/online-courses-lms/canvas-lms/
  slug: canvas-lms
  url: https://github.com/instructure/canvas-lms
- anchor: open-edx
  counts:
    declared: 0
    observed: 8
  evidence:
  - route: dependency manifest
    url: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
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
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
    tier: observed
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
    says: ships the Mailchimp SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
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
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    credit: null
    layer: common
    name: Optimizely
    provider: optimizely
    says: ships the Optimizely SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Sailthru
    provider: sailthru
    says: ships the Sailthru SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Segment
    provider: segment
    says: ships the Segment SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    credit: null
    layer: common
    name: Snowflake
    provider: snowflake
    says: ships the Snowflake SDK or integration code
    source: https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
    tier: observed
  kind: self-hosted
  name: Open edX
  page: /applications/online-courses-lms/open-edx/
  slug: open-edx
  url: https://github.com/openedx/edx-platform
- anchor: chamilo
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: common
    name: Amazon SES
    provider: amazon-ses
    says: ships the Amazon SES SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: ships the Azure Blob Storage SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: BigBlueButton
    provider: bigbluebutton
    says: ships the BigBlueButton SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    name: Brevo
    provider: brevo
    says: ships the Brevo SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Facebook
    provider: facebook
    says: ships the Facebook SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    credit: null
    layer: common
    name: Google Maps
    provider: google-maps
    says: ships the Google Maps SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Keycloak
    provider: keycloak
    says: ships the Keycloak SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    name: Mailjet
    provider: mailjet
    says: ships the Mailjet SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Microsoft
    provider: microsoft-entra
    says: ships the Microsoft SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
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
    name: Microsoft Graph
    provider: microsoft-graph
    says: ships the Microsoft Graph SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-930
      key: AE-930
      name: Browser Document Editing (WOPI)
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: ONLYOFFICE
    provider: onlyoffice
    says: ships the ONLYOFFICE SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
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
    says: ships the Stripe SDK or integration code
    source: https://github.com/chamilo/chamilo-lms/blob/master/composer.json
    tier: observed
  kind: self-hosted
  name: Chamilo
  page: /applications/online-courses-lms/chamilo/
  slug: chamilo
  url: https://github.com/chamilo/chamilo-lms
- anchor: coursera
  counts:
    declared: 0
    observed: 4
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Kochava
    provider: kochava
    says: ships the Kochava SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
    tier: observed
  kind: commercial
  name: Coursera
  page: /applications/online-courses-lms/coursera/
  slug: coursera
  url: https://www.coursera.org/
- anchor: udemy
  counts:
    declared: 0
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Amplitude
    provider: amplitude
    says: ships the Amplitude SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Branch
    provider: branch-io
    says: ships the Branch SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Facebook Login
    provider: facebook
    says: ships the Facebook Login SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Firebase
    provider: firebase
    says: ships the Firebase SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Google AdMob
    provider: google-admob
    says: ships the Google AdMob SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
    tier: observed
  kind: commercial
  name: Udemy
  page: /applications/online-courses-lms/udemy/
  slug: udemy
  url: https://www.udemy.com/
- anchor: learnworlds
  counts:
    declared: 55
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.learnworlds.com/integrations/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-3780
      key: content-compliance-standards-management
      name: Content Compliance & Standards Management
      url: /capabilities/content-compliance-standards-management/
      via_parent: null
    credit: null
    layer: common
    name: accessiBe
    provider: accessibe
    says: lists accessiBe as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4720.50
      key: graduation-credentialing
      name: Graduation & Credentialing
      url: /capabilities/graduation-credentialing/
      via_parent: null
    credit: null
    layer: domain
    name: Accredible
    provider: accredible
    says: lists Accredible as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: ActiveCampaign
    provider: activecampaign
    says: lists ActiveCampaign as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Afterpay
    provider: afterpay
    says: lists Afterpay as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Apple Pay
    provider: apple-pay
    says: lists Apple Pay as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: AWeber
    provider: aweber
    says: lists AWeber as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Bancontact
    provider: bancontact
    says: lists Bancontact as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: BDOW!
    provider: bdow
    says: lists BDOW! as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    credit: null
    layer: common
    name: Calendly
    provider: calendly
    says: lists Calendly as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Constant Contact
    provider: constant-contact
    says: lists Constant Contact as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4720.50
      key: graduation-credentialing
      name: Graduation & Credentialing
      url: /capabilities/graduation-credentialing/
      via_parent: null
    credit: null
    layer: domain
    name: Credly
    provider: credly
    says: lists Credly as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Facebook Pixel
    provider: facebook
    says: lists Facebook Pixel as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: FOMO
    provider: fomo-com
    says: lists FOMO as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Freshchat
    provider: freshchat
    says: lists Freshchat as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: FullSession
    provider: fullsession
    says: lists FullSession as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: FullStory
    provider: fullstory
    says: lists FullStory as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: GetResponse
    provider: getresponse
    says: lists GetResponse as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Google Meet
    provider: google-meet
    says: lists Google Meet as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Google Pay
    provider: google-pay
    says: lists Google Pay as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Google Search
    provider: google-search-console
    says: lists Google Search as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
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
    name: Hotjar
    provider: hotjar
    says: lists Hotjar as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
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
    name: iDEAL
    provider: ideal
    says: lists iDEAL as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Integrately
    provider: integrately
    says: lists Integrately as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Kit
    provider: convertkit
    says: lists Kit as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    credit: null
    layer: common
    name: Klarna
    provider: klarna
    says: lists Klarna as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
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
    name: MailerLite
    provider: mailerlite
    says: lists MailerLite as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Teams
    provider: microsoft-teams
    says: lists Microsoft Teams as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Mixpanel
    provider: mixpanel
    says: lists Mixpanel as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Moosend
    provider: moosend
    says: lists Moosend as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Mouseflow
    provider: mouseflow
    says: lists Mouseflow as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Olark
    provider: olark
    says: lists Olark as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: OptinMonster
    provider: optinmonster
    says: lists OptinMonster as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Pabbly
    provider: pabbly
    says: lists Pabbly as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
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
    name: Przelewy24
    provider: przelewy24
    says: lists Przelewy24 as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: common
    name: Quaderno
    provider: quaderno
    says: lists Quaderno as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: ReferralCandy
    provider: referralcandy
    says: lists ReferralCandy as an integration
    source: https://www.learnworlds.com/integrations/
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
    name: Refersion
    provider: refersion
    says: lists Refersion as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    credit: null
    layer: common
    name: Stripe Tax
    provider: stripe
    says: lists Stripe Tax as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: Tawk.to
    provider: tawk-to
    says: lists Tawk.to as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Vimeo
    provider: vimeo
    says: lists Vimeo as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Webex
    provider: webex
    says: lists Webex as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: common
    name: Weglot
    provider: weglot
    says: lists Weglot as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    credit: null
    layer: domain
    name: Wistia
    provider: wistia
    says: lists Wistia as an integration
    source: https://www.learnworlds.com/integrations/
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
    source: https://www.learnworlds.com/integrations/
    tier: declared
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
    says: lists Zendesk as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.learnworlds.com/integrations/
    tier: declared
  kind: commercial
  name: LearnWorlds
  page: /applications/online-courses-lms/learnworlds/
  slug: learnworlds
  url: https://www.learnworlds.com/
- anchor: thinkific
  counts:
    declared: 13
    observed: 0
  evidence:
  - route: integrations page
    url: https://www.thinkific.com/app-store/
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    credit: null
    layer: common
    name: Google Analytics (GA4)
    provider: google-analytics
    says: lists Google Analytics (GA4) as an integration
    source: https://www.thinkific.com/app-store/
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
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4790
      key: educational-content-learning-resource-management
      name: Educational Content & Learning Resource Management
      url: /capabilities/educational-content-learning-resource-management/
      via_parent: null
    credit: null
    layer: domain
    name: iorad
    provider: iorad
    says: lists iorad as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: common
    name: JivoChat
    provider: jivochat
    says: lists JivoChat as an integration
    source: https://www.thinkific.com/app-store/
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
    name: Kit
    provider: convertkit
    says: lists Kit as an integration
    source: https://www.thinkific.com/app-store/
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
    name: Meta Pixel
    provider: facebook
    says: lists Meta Pixel as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    credit: null
    layer: common
    name: QuickBooks Sync
    provider: quickbooks
    says: lists QuickBooks Sync as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    credit: null
    layer: common
    name: Shopify
    provider: shopify
    says: lists Shopify as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: Smartarget
    provider: smartarget
    says: lists Smartarget as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4790
      key: educational-content-learning-resource-management
      name: Educational Content & Learning Resource Management
      url: /capabilities/educational-content-learning-resource-management/
      via_parent: null
    credit: null
    layer: domain
    name: ThingLink
    provider: thinglink
    says: lists ThingLink as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    credit: null
    layer: common
    name: WiserNotify
    provider: wisernotify
    says: lists WiserNotify as an integration
    source: https://www.thinkific.com/app-store/
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
    source: https://www.thinkific.com/app-store/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    credit: null
    layer: domain
    name: Zoom
    provider: zoom
    says: lists Zoom as an integration
    source: https://www.thinkific.com/app-store/
    tier: declared
  kind: commercial
  name: Thinkific
  page: /applications/online-courses-lms/thinkific/
  slug: thinkific
  url: https://www.thinkific.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: online-courses-lms
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Education
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Education
  store: google-play
  url: https://play.google.com/store/apps/category/EDUCATION
- category: Learning and Courses
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#learning-and-courses
- category: Education
  store: salesforce-appexchange
  url: https://appexchange.salesforce.com/
- category: Education
  store: zapier
  url: https://zapier.com/apps
name: Online Courses & Learning Management
needs:
- capability:
    attribution: Turbo EA
    id: BC-4790
    key: educational-content-learning-resource-management
    name: Educational Content & Learning Resource Management
    url: /capabilities/educational-content-learning-resource-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: course content pulled in from external repositories and authoring tools (Moodle repositories, ThingLink, iorad)
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  fit: exact
  layer: domain
  why: 'live classes: virtual classroom and webinar tools'
- capability:
    attribution: API Evangelist extension
    id: AE-170.10.10
    key: AE-170.10.10
    name: Video Hosting & Encoding
    url: /capabilities/video-platforms/
    via_parent: Video Platforms
  fit: exact
  layer: domain
  why: lecture video hosting and streaming
- capability:
    attribution: Turbo EA
    id: BC-4720.50
    key: graduation-credentialing
    name: Graduation & Credentialing
    url: /capabilities/graduation-credentialing/
    via_parent: null
  fit: exact
  layer: domain
  why: digital certificates and badges for course completion
- capability:
    attribution: Turbo EA
    id: BC-4700.30
    key: curriculum-mapping-alignment
    name: Curriculum Mapping & Alignment
    url: /capabilities/curriculum-mapping-alignment/
    via_parent: null
  fit: exact
  layer: domain
  why: learning-standards libraries for outcome alignment (Academic Benchmarks)
- capability:
    attribution: Turbo EA
    id: BC-4740.60.10
    key: BC-4740.60.10
    name: Plagiarism Detection
    url: /capabilities/academic-integrity-management/
    via_parent: Academic Integrity Management
  fit: exact
  layer: domain
  why: plagiarism / originality checking of submissions; no node fits exactly
- capability:
    attribution: Turbo EA
    id: BC-830.30
    key: knowledge-sharing-collaboration-management
    name: Knowledge Sharing & Collaboration Management
    url: /capabilities/knowledge-sharing-collaboration-management/
    via_parent: null
  fit: nearest
  layer: domain
  why: collaborative document editing and social bookmarking inside courses
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: learner sign-in through social, school (Clever) and workforce IdPs
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: selling courses and enrolment fees
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.10
    key: AE-140.30.10
    name: Buy Now, Pay Later
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: buy-now-pay-later at course checkout
- capability:
    attribution: API Evangelist extension
    id: AE-140.30.20
    key: AE-140.30.20
    name: Digital & Mobile Wallets
    url: /capabilities/consumer-payment-options/
    via_parent: Consumer Payment Options
  fit: exact
  layer: common
  why: wallets at course checkout
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  fit: exact
  layer: common
  why: VAT / sales tax on digital course sales
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: nearest
  layer: common
  why: syncing course revenue to bookkeeping
- capability:
    attribution: API Evangelist extension
    id: AE-140.10.10
    key: AE-140.10.10
    name: Hosted Storefronts
    url: /capabilities/storefront-platforms/
    via_parent: Storefront Platforms
  fit: exact
  layer: common
  why: selling courses through a hosted storefront
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: student records synced to CRM
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: transactional mail (enrolment, notifications)
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: marketing email to learners
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: common
  why: SMS for MFA and notifications
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  fit: exact
  layer: common
  why: mobile push notifications
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: live chat and help desk on the school site
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: learner behaviour analytics and session replay
- capability:
    attribution: Turbo EA
    id: BC-420.10
    key: customer-data-management
    name: Customer Data Management
    url: /capabilities/customer-data-management/
    via_parent: null
  fit: exact
  layer: common
  why: event pipeline / CDP
- capability:
    attribution: Turbo EA
    id: BC-4280
    key: product-telemetry-experimentation-management
    name: Product Telemetry & Experimentation Management
    url: /capabilities/product-telemetry-experimentation-management/
    via_parent: null
  fit: exact
  layer: common
  why: A/B experiments on the learner experience
- capability:
    attribution: Turbo EA
    id: BC-600.60.50
    key: BC-600.60.50
    name: Integration and API Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: common
  why: event streams, queues and warehouse export of learning events
- capability:
    attribution: Turbo EA
    id: BC-400.60
    key: digital-marketing-management
    name: Digital Marketing Management
    url: /capabilities/digital-marketing-management/
    via_parent: null
  fit: exact
  layer: common
  why: pixels, lead capture, affiliates and SEO for course sales
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  fit: exact
  layer: common
  why: social-proof popups for course sales
- capability:
    attribution: API Evangelist extension
    id: AE-911
    key: AE-911
    name: Tag Management
    url: /capabilities/product-telemetry-instrumentation/
    via_parent: Product Telemetry Instrumentation
  fit: exact
  layer: common
  why: tag management on the school site
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: no-code automation between the school and other tools
- capability:
    attribution: Turbo EA
    id: BC-2800.10
    key: scheduling-appointment-management
    name: Scheduling & Appointment Management
    url: /capabilities/scheduling-appointment-management/
    via_parent: null
  fit: exact
  layer: common
  why: booking coaching sessions
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  fit: exact
  layer: common
  why: course file storage
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: crash reporting, error monitoring and APM
- capability:
    attribution: API Evangelist extension
    id: AE-120.50.10
    key: AE-120.50.10
    name: IP Geolocation
    url: /capabilities/device-ip-location/
    via_parent: Device & IP Location
  fit: exact
  layer: common
  why: IP geolocation for country-aware enrolment and pricing
- capability:
    attribution: API Evangelist extension
    id: AE-120.20.10
    key: AE-120.20.10
    name: Base Map Tiles
    url: /capabilities/maps-tiles/
    via_parent: Maps & Tiles
  fit: exact
  layer: common
  why: map widgets on course/session forms
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: common
  why: translating the school site
- capability:
    attribution: Turbo EA
    id: BC-3780
    key: content-compliance-standards-management
    name: Content Compliance & Standards Management
    url: /capabilities/content-compliance-standards-management/
    via_parent: null
  fit: nearest
  layer: common
  why: web accessibility overlay
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: mobile install attribution and deep links
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app ads
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: LLM providers for the LMS AI subsystem (course generation, summaries)
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: agent
  why: self-hosted local model runtime
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-150.60
      key: AE-150.60
      name: Video Calling
      url: /capabilities/video-calling/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 61.1
      apps:
      - Canvas LMS
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 64.2
      mcp:
        source: https://github.com/WebexSamples/webex-messaging-mcp-server
        status: verified
      name: Webex
      slug: webex
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Calling
      - Collaboration
      - Communications
      - Enterprise
      tier: observed
      url: /providers/webex/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Chamilo
      - Moodle
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: BigBlueButton
      slug: bigbluebutton
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      - https://github.com/moodle/moodle/tree/main/public/mod/bigbluebuttonbn
      status: profiled
      tags:
      - Company
      - Education
      - Open Source
      - Video Conferencing
      tier: observed
      url: /providers/bigbluebutton/
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - LearnWorlds
      - Thinkific
      band: strong
      in_catalog: true
      kin_score: 56.2
      mcp:
        source: https://developers.zoom.us/docs/mcp/
        status: verified
      name: Zoom
      slug: zoom
      sources:
      - https://www.learnworlds.com/integrations/
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Video
      - Zoom
      tier: declared
      url: /providers/zoom/
    - agent_band: null
      agent_readiness: null
      apps:
      - Canvas LMS
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Adobe Connect
      slug: adobe-connect
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: queued for profiling
      tags: []
      tier: observed
      url: null
    - agent_band: agent-ready
      agent_readiness: 34.2
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 59.0
      mcp:
        status: none
      name: Microsoft Teams
      slug: microsoft-teams
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Chat
      - Collaboration
      - Communications
      - Microsoft Teams
      tier: declared
      url: /providers/microsoft-teams/
    - agent_band: agent-aware
      agent_readiness: 17.2
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 27.7
      mcp:
        status: none
      name: Google Meet
      slug: google-meet
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Google
      - Google Workspace
      - Meetings
      - Recording
      tier: declared
      url: /providers/google-meet/
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.3
      apps:
      - Canvas LMS
      - Moodle
      band: exemplar
      in_catalog: true
      kin_score: 67.1
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: OneDrive
      slug: microsoft-onedrive
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: observed
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 45.8
      apps:
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 47.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: observed
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 19.0
      apps:
      - Moodle
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Nextcloud
      slug: nextcloud
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Collaboration
      - File Sharing
      - File Sync
      - Self-Hosted
      tier: observed
      url: /providers/nextcloud/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.10.10
      key: AE-170.10.10
      name: Video Hosting & Encoding
      url: /capabilities/video-platforms/
      via_parent: Video Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.8
      apps:
      - LearnWorlds
      - Moodle
      band: thin
      in_catalog: true
      kin_score: 38.4
      mcp:
        source: https://developer.vimeo.com/api/mcp-server
        status: documented
      name: Vimeo
      slug: vimeo
      sources:
      - https://github.com/moodle/moodle/tree/main/public/media/player
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Live Streaming
      - Streaming
      - Video
      - Video Hosting
      tier: observed
      url: /providers/vimeo/
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Moodle
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp: &id001
        status: none
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/moodle/moodle/tree/main/public/media/player
      status: profiled
      tags: &id002
      - Google
      - Media
      - Video
      - YouTube
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-aware
      agent_readiness: 21.3
      apps:
      - Canvas LMS
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp:
        source: https://github.com/kaltura/mcp-events
        status: verified
      name: Kaltura
      slug: kaltura
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Live Streaming
      - Media Management
      - Transcoding
      - Video
      tier: observed
      url: /providers/kaltura/
    - agent_band: agent-ready
      agent_readiness: 35.7
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 75.8
      mcp:
        source: https://docs.wistia.com/docs/mcp-server-guide
        status: documented
      name: Wistia
      slug: wistia
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Lead Generation
      - Video Analytics
      - Video Hosting
      - Video Marketing
      tier: declared
      url: /providers/wistia/
  - capability:
      attribution: Turbo EA
      id: BC-4790
      key: educational-content-learning-resource-management
      name: Educational Content & Learning Resource Management
      url: /capabilities/educational-content-learning-resource-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 43.4
      apps:
      - Moodle
      band: strong
      in_catalog: true
      kin_score: 62.6
      mcp: *id001
      name: YouTube
      slug: youtube
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/youtube/
    - agent_band: agent-aware
      agent_readiness: 25.6
      apps:
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 48.6
      mcp:
        status: none
      name: Flickr
      slug: flickr
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Photography
      - Photos
      - Public APIs
      - Social Media
      tier: observed
      url: /providers/flickr/
    - agent_band: agent-aware
      agent_readiness: 15.1
      apps:
      - Thinkific
      band: emerging
      in_catalog: true
      kin_score: 19.8
      mcp:
        status: none
      name: iorad
      slug: iorad
      sources:
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Company
      - Software Adoption
      - Training
      - Tutorial
      tier: declared
      url: /providers/iorad/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Thinkific
      band: emerging
      in_catalog: true
      kin_score: 18.4
      mcp:
        status: none
      name: ThingLink
      slug: thinglink
      sources:
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Company
      - EdTech
      - Education
      - Interactive Media
      tier: declared
      url: /providers/thinglink/
  - capability:
      attribution: Turbo EA
      id: BC-4720.50
      key: graduation-credentialing
      name: Graduation & Credentialing
      url: /capabilities/graduation-credentialing/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.1
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 29.7
      mcp:
        status: none
      name: Credly
      slug: credly
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Badging
      - Certification
      - Digital Credentials
      - Open Badges
      tier: declared
      url: /providers/credly/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        status: none
      name: Accredible
      slug: accredible
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Badges
      - Certificates
      - Digital Credentials
      - Open Badges
      tier: declared
      url: /providers/accredible/
  - capability:
      attribution: Turbo EA
      id: BC-4790.30
      key: BC-4790.30
      name: Open Educational Resource Management
      url: /capabilities/educational-content-learning-resource-management/
      via_parent: Educational Content & Learning Resource Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 28.9
      apps:
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 45.8
      mcp:
        status: none
      name: Wikimedia Commons
      slug: wikimedia
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Encyclopedia
      - Open Knowledge
      - Wikimedia
      - Wikipedia
      tier: observed
      url: /providers/wikimedia/
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Moodle
      band: minimal
      in_catalog: true
      kin_score: 3.8
      mcp:
        status: unknown
      name: MERLOT
      slug: merlot
      sources:
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Community
      - Company
      - Education
      - Open Source
      tier: observed
      url: /providers/merlot/
  - capability:
      attribution: Turbo EA
      id: BC-4740.60.10
      key: BC-4740.60.10
      name: Plagiarism Detection
      url: /capabilities/academic-integrity-management/
      via_parent: Academic Integrity Management
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Canvas LMS
      band: thin
      in_catalog: true
      kin_score: 35.9
      mcp:
        status: none
      name: Turnitin
      slug: turnitin
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Academic Integrity
      - Company
      - EdTech
      - Education
      tier: observed
      url: /providers/turnitin/
    - agent_band: null
      agent_readiness: null
      apps:
      - Canvas LMS
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: VeriCite
      slug: vericite
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-170.60.40
      key: AE-170.60.40
      name: Bookmarks, Read-Later & Feed Readers
      url: /capabilities/news-publishing/
      via_parent: News & Publishing
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Canvas LMS
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: unknown
      name: Diigo
      slug: diigo
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/diigo/
  - capability:
      attribution: API Evangelist extension
      id: AE-930
      key: AE-930
      name: Browser Document Editing (WOPI)
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Chamilo
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: ONLYOFFICE
      slug: onlyoffice
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: Turbo EA
      id: BC-4700.30
      key: curriculum-mapping-alignment
      name: Curriculum Mapping & Alignment
      url: /capabilities/curriculum-mapping-alignment/
      via_parent: null
    providers:
    - agent_band: null
      agent_readiness: null
      apps:
      - Canvas LMS
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Academic Benchmarks
      slug: academic-benchmarks
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Canvas LMS
      - Chamilo
      - Coursera
      - Moodle
      - Udemy
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: &id003
        status: none
      name: Facebook
      slug: facebook
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      - https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
      status: profiled
      tags: &id004
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 33.5
      apps:
      - Canvas LMS
      - Chamilo
      - Moodle
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        status: none
      name: Microsoft
      slug: microsoft-entra
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      - https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: observed
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 47.4
      apps:
      - Canvas LMS
      - Moodle
      band: exemplar
      in_catalog: true
      kin_score: 76.4
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      - https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: observed
      url: /providers/linkedin/
    - agent_band: agent-aware
      agent_readiness: 28.3
      apps:
      - Canvas LMS
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 41.9
      mcp:
        status: none
      name: Clever
      slug: clever
      sources:
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      - https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
      status: profiled
      tags:
      - EdTech
      - Education
      - K-12
      - SSO
      tier: observed
      url: /providers/clever/
    - agent_band: agent-aware
      agent_readiness: 19.6
      apps:
      - Canvas LMS
      - Moodle
      band: thin
      in_catalog: true
      kin_score: 36.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      - https://github.com/moodle/moodle/tree/main/public/lib/classes/oauth2/service
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 63.4
      apps:
      - Canvas LMS
      band: exemplar
      in_catalog: true
      kin_score: 85.4
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Canvas LMS
      band: strong
      in_catalog: true
      kin_score: 55.2
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://github.com/instructure/canvas-lms/tree/master/app/models/authentication_provider
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: observed
      url: /providers/apple/
    - agent_band: agent-aware
      agent_readiness: 17.6
      apps:
      - Chamilo
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: observed
      url: /providers/keycloak/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - LearnWorlds
      - Open edX
      band: exemplar
      in_catalog: true
      kin_score: 78.3
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: observed
      url: /providers/mailchimp/
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - LearnWorlds
      - Thinkific
      band: exemplar
      in_catalog: true
      kin_score: 79.6
      mcp:
        status: none
      name: Kit
      slug: convertkit
      sources:
      - https://www.learnworlds.com/integrations/
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Automation
      - Creator Economy
      - Email Marketing
      - Subscribers
      tier: declared
      url: /providers/convertkit/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Open edX
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp:
        status: none
      name: Sailthru
      slug: sailthru
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      status: profiled
      tags:
      - Company
      - Email Marketing
      - Marketing Automation
      - Personalization
      tier: observed
      url: /providers/sailthru/
    - agent_band: agent-ready
      agent_readiness: 53.7
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://developers.activecampaign.com/page/mcp
        status: documented
      name: ActiveCampaign
      slug: activecampaign
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - CRM
      - Email Marketing
      - Marketing Automation
      - Sales Automation
      tier: declared
      url: /providers/activecampaign/
    - agent_band: agent-ready
      agent_readiness: 48.9
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        status: none
      name: GetResponse
      slug: getresponse
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Email Marketing
      - Landing Pages
      - Marketing Automation
      - Webinars
      tier: declared
      url: /providers/getresponse/
    - agent_band: agent-ready
      agent_readiness: 39.6
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 72.2
      mcp:
        source: https://github.com/aweber/aweber-mcp
        status: verified
      name: AWeber
      slug: aweber
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Email
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/aweber/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://developers.mailerlite.com/
        status: documented
      name: MailerLite
      slug: mailerlite
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Automation
      - Email Marketing
      - Newsletters
      - Subscribers
      tier: declared
      url: /providers/mailerlite/
    - agent_band: agent-ready
      agent_readiness: 32.1
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 70.9
      mcp:
        status: none
      name: Constant Contact
      slug: constant-contact
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Contacts
      - Email Marketing
      - Event
      tier: declared
      url: /providers/constant-contact/
    - agent_band: agent-ready
      agent_readiness: 34.3
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 63.7
      mcp:
        status: none
      name: Moosend
      slug: moosend
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Mailing Lists
      - Marketing Automation
      tier: declared
      url: /providers/moosend/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - Coursera
      - LearnWorlds
      - Thinkific
      - Udemy
      band: developing
      in_catalog: true
      kin_score: 42.7
      mcp: *id003
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/facebook/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 70.4
      mcp:
        status: none
      name: Google Search
      slug: google-search-console
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Google
      - Indexing
      - Search
      tier: declared
      url: /providers/google-search-console/
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 63.7
      mcp:
        status: none
      name: Refersion
      slug: refersion
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Affiliate Marketing
      - E-Commerce
      - Influencer Marketing
      - Referral Tracking
      tier: declared
      url: /providers/refersion/
    - agent_band: agent-aware
      agent_readiness: 25.2
      apps:
      - LearnWorlds
      band: developing
      in_catalog: true
      kin_score: 53.8
      mcp:
        status: none
      name: OptinMonster
      slug: optinmonster
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Company
      - Conversion Optimization
      - Lead Generation
      - Marketing
      tier: declared
      url: /providers/optinmonster/
    - agent_band: agent-aware
      agent_readiness: 15.8
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 28.3
      mcp:
        status: none
      name: ReferralCandy
      slug: referralcandy
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Affiliates
      - Company
      - E-Commerce
      - Referrals
      tier: declared
      url: /providers/referralcandy/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - LearnWorlds
      band: emerging
      in_catalog: true
      kin_score: 11.6
      mcp:
        status: unknown
      name: BDOW!
      slug: bdow
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/bdow/
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.8
      apps:
      - LearnWorlds
      - Thinkific
      band: exemplar
      in_catalog: true
      kin_score: 73.9
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://www.learnworlds.com/integrations/
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: declared
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.7
      apps:
      - Udemy
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
        status: verified
      name: Amplitude
      slug: amplitude
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Experimentation
      - Feature Flags
      tier: observed
      url: /providers/amplitude/
    - agent_band: agent-ready
      agent_readiness: 35.4
      apps:
      - Canvas LMS
      band: strong
      in_catalog: true
      kin_score: 56.4
      mcp:
        source: https://support.pendo.io/hc/en-us/articles/41102236924955
        status: verified
      name: Pendo
      slug: pendoio
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
      status: profiled
      tags:
      - Company
      - Digital Adoption
      - Product Analytics
      - Product Experience
      tier: observed
      url: /providers/pendoio/
    - agent_band: agent-ready
      agent_readiness: 48.3
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 60.3
      mcp:
        source: https://docs.mixpanel.com/docs/features/mcp
        status: verified
      name: Mixpanel
      slug: mixpanel
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Event Tracking
      - Product Analytics
      tier: declared
      url: /providers/mixpanel/
    - agent_band: agent-ready
      agent_readiness: 30.6
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 37.1
      mcp:
        source: https://developer.fullstory.com/mcp/introduction/
        status: documented
      name: FullStory
      slug: fullstory
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Behavioral Analytics
      - Digital Experience
      - Product Analytics
      - Session Replay
      tier: declared
      url: /providers/fullstory/
    - agent_band: agent-aware
      agent_readiness: 27.8
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 26.7
      mcp:
        status: none
      name: Hotjar
      slug: hotjar
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Personalization
      - Surveys
      - Tracking
      tier: declared
      url: /providers/hotjar/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - LearnWorlds
      band: emerging
      in_catalog: true
      kin_score: 15.6
      mcp:
        source: https://mouseflow.com/platform/ai/mcp-server/
        status: verified
      name: Mouseflow
      slug: mouseflow
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/mouseflow/
    - agent_band: agent-aware
      agent_readiness: 18.7
      apps:
      - LearnWorlds
      band: emerging
      in_catalog: true
      kin_score: 14.6
      mcp:
        source: https://docs.fullsession.io/mcp-server
        status: verified
      name: FullSession
      slug: fullsession
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Session Replay
      - Web
      tier: declared
      url: /providers/fullsession/
  - capability:
      attribution: Turbo EA
      id: BC-1340.20
      key: payment-processing-management
      name: Payment Processing Management
      url: /capabilities/payment-processing-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - Chamilo
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: &id005
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags: &id006
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
    - agent_band: agent-ready
      agent_readiness: 37.1
      apps:
      - LearnWorlds
      - Moodle
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        source: https://developer.paypal.com/tools/mcp-server/
        status: verified
      name: PayPal
      slug: paypal
      sources:
      - https://github.com/moodle/moodle/tree/main/public/payment/gateway
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Billing
      - Commerce
      - Disputes
      - PayPal
      tier: observed
      url: /providers/paypal/
    - agent_band: agent-native
      agent_readiness: 50.8
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 66.0
      mcp:
        status: none
      name: Bancontact
      slug: bancontact
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Banking
      - Belgium
      - Debit Cards
      - E-Commerce
      tier: declared
      url: /providers/bancontact/
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 39.0
      mcp:
        status: none
      name: Przelewy24
      slug: przelewy24
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - BLIK
      - Bank Transfers
      - Payment Gateway
      - Payments
      tier: declared
      url: /providers/przelewy24/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - LearnWorlds
      band: minimal
      in_catalog: true
      kin_score: 4.1
      mcp:
        status: unknown
      name: iDEAL
      slug: ideal
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Banking
      - E-Commerce
      - Europe
      - Payments
      tier: declared
      url: /providers/ideal/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 72.8
      mcp:
        status: none
      name: Zendesk
      slug: zendesk
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 31.7
      apps:
      - LearnWorlds
      band: developing
      in_catalog: true
      kin_score: 52.5
      mcp:
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom
      slug: intercom
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
    - agent_band: agent-aware
      agent_readiness: 22.8
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        status: none
      name: Freshchat
      slug: freshchat
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Conversational Engagement
      - Customer Messaging
      - Customer Service
      - Live Chat
      tier: declared
      url: /providers/freshchat/
    - agent_band: agent-ready
      agent_readiness: 43.3
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 31.4
      mcp:
        status: none
      name: Olark
      slug: olark
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Chatbots
      - Customer Engagement
      - Customer Service
      - Live Chat
      tier: declared
      url: /providers/olark/
    - agent_band: agent-aware
      agent_readiness: 20.1
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 26.2
      mcp:
        status: none
      name: Tawk.to
      slug: tawk-to
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Company
      - Customer Service
      - FreeSoftware
      - Live Chat
      tier: declared
      url: /providers/tawk-to/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Thinkific
      band: emerging
      in_catalog: true
      kin_score: 12.3
      mcp:
        status: none
      name: JivoChat
      slug: jivochat
      sources:
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Live Chat
      - Messaging
      tier: declared
      url: /providers/jivochat/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Canvas LMS
      - Coursera
      - Udemy
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: &id007
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Google CrashLytics
      slug: firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.instructure.candroid/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
      - https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
      status: profiled
      tags: &id008
      - Application Development
      - Backend-as-a-Service
      - Company
      - Mobile
      tier: observed
      url: /providers/firebase/
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Canvas LMS
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 49.6
      apps:
      - Canvas LMS
      band: exemplar
      in_catalog: true
      kin_score: 79.2
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: observed
      url: /providers/datadog/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 39.4
      apps:
      - Chamilo
      - Open edX
      band: exemplar
      in_catalog: true
      kin_score: 80.6
      mcp:
        status: none
      name: Amazon SES
      slug: amazon-ses
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      status: profiled
      tags:
      - Amazon Web Services
      - Email
      - Email Deliverability
      - Email Service
      tier: observed
      url: /providers/amazon-ses/
    - agent_band: agent-ready
      agent_readiness: 57.2
      apps:
      - Chamilo
      band: exemplar
      in_catalog: true
      kin_score: 82.2
      mcp:
        source: https://developers.brevo.com/docs/mcp-protocol
        status: verified
      name: Brevo
      slug: brevo
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Email Marketing
      - Marketing
      - Marketing Automation
      - Transactional Email
      tier: observed
      url: /providers/brevo/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Chamilo
      band: exemplar
      in_catalog: true
      kin_score: 70.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft Graph
      slug: microsoft-graph
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Azure AD
      - Collaboration
      - Contacts
      - Microsoft Graph
      tier: observed
      url: /providers/microsoft-graph/
    - agent_band: agent-aware
      agent_readiness: 23.4
      apps:
      - Chamilo
      band: developing
      in_catalog: true
      kin_score: 50.1
      mcp:
        source: https://github.com/mailgun/mailjet-mcp-server
        status: verified
      name: Mailjet
      slug: mailjet
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Email
      - Email Delivery
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/mailjet/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 66.2
      apps:
      - LearnWorlds
      - Thinkific
      band: exemplar
      in_catalog: true
      kin_score: 72.0
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://www.learnworlds.com/integrations/
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Integration
      - Workflow Automation
      - Zapier
      - iPaaS
      tier: declared
      url: /providers/zapier/
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        status: none
      name: Pabbly
      slug: pabbly
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Automation
      - Billing
      - Email Marketing
      - Subscription Billing
      tier: declared
      url: /providers/pabbly/
    - agent_band: agent-aware
      agent_readiness: 19.8
      apps:
      - LearnWorlds
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: Integrately
      slug: integrately
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Automation
      - Business Process Automation
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/integrately/
    - agent_band: agent-ready
      agent_readiness: 43.9
      apps:
      - LearnWorlds
      band: developing
      in_catalog: true
      kin_score: 43.5
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.learnworlds.com/integrations/
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
      id: BC-3710.30
      key: asset-storage-tiering
      name: Asset Storage & Tiering
      url: /capabilities/asset-storage-tiering/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Canvas LMS
      - Moodle
      band: exemplar
      in_catalog: true
      kin_score: 71.2
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      - https://github.com/moodle/moodle/tree/main/public/repository
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.3
      apps:
      - Chamilo
      band: exemplar
      in_catalog: true
      kin_score: 71.7
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 40.9
      apps:
      - Chamilo
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.60
      key: AE-140.60
      name: Reviews & Social Proof
      url: /capabilities/reviews-social-proof/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.9
      apps:
      - Thinkific
      band: emerging
      in_catalog: true
      kin_score: 19.7
      mcp:
        status: none
      name: WiserNotify
      slug: wisernotify
      sources:
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Company
      - Notification
      - Real-Time
      - Software-as-a-Service
      tier: declared
      url: /providers/wisernotify/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Thinkific
      band: minimal
      in_catalog: true
      kin_score: 2.9
      mcp:
        source: https://api-v2.smartarget.online/api/mcp/message
        status: verified
      name: Smartarget
      slug: smartarget
      sources:
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Banking APIs
      - Company
      - Fintech
      - Payments
      tier: declared
      url: /providers/smartarget/
    - agent_band: null
      agent_readiness: null
      apps:
      - LearnWorlds
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: FOMO
      slug: fomo-com
      sources:
      - https://www.learnworlds.com/integrations/
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.10
      key: AE-140.30.10
      name: Buy Now, Pay Later
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-native
      agent_readiness: 46.0
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        status: none
      name: Klarna
      slug: klarna
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Cards
      - Fintech
      - Payments
      tier: declared
      url: /providers/klarna/
    - agent_band: agent-aware
      agent_readiness: 13.0
      apps:
      - LearnWorlds
      band: minimal
      in_catalog: true
      kin_score: 9.3
      mcp:
        status: none
      name: Afterpay
      slug: afterpay
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Buy Now Pay Later
      - Consumer
      - Fintech
      - Payments
      tier: declared
      url: /providers/afterpay/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.7
      apps:
      - LearnWorlds
      - Thinkific
      band: exemplar
      in_catalog: true
      kin_score: 94.6
      mcp:
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://www.learnworlds.com/integrations/
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.30.20
      key: AE-140.30.20
      name: Digital & Mobile Wallets
      url: /capabilities/consumer-payment-options/
      via_parent: Consumer Payment Options
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.1
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 66.2
      mcp:
        status: none
      name: Google Pay
      slug: google-pay
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Agentic Commerce
      - Checkout
      - Contactless Payments
      - Digital Wallet
      tier: declared
      url: /providers/google-pay/
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - LearnWorlds
      band: developing
      in_catalog: true
      kin_score: 43.6
      mcp:
        status: none
      name: Apple Pay
      slug: apple-pay
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Apple
      - Contactless Payments
      - Digital Wallet
      - E-Commerce
      tier: declared
      url: /providers/apple-pay/
  - capability:
      attribution: API Evangelist extension
      id: AE-140.10.10
      key: AE-140.10.10
      name: Hosted Storefronts
      url: /capabilities/storefront-platforms/
      via_parent: Storefront Platforms
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.5
      apps:
      - LearnWorlds
      - Thinkific
      band: exemplar
      in_catalog: true
      kin_score: 84.6
      mcp:
        source: https://shopify.dev/docs/apps/build/devmcp
        status: verified
      name: Shopify
      slug: shopify
      sources:
      - https://www.learnworlds.com/integrations/
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Commerce
      - E-Commerce
      - Payments
      - Retail
      tier: declared
      url: /providers/shopify/
  - capability:
      attribution: Turbo EA
      id: BC-220.20
      key: indirect-tax-management
      name: Indirect Tax Management
      url: /capabilities/indirect-tax-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 58.5
      apps:
      - LearnWorlds
      band: exemplar
      in_catalog: true
      kin_score: 81.5
      mcp: *id005
      name: Stripe Tax
      slug: stripe
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags: *id006
      tier: declared
      url: /providers/stripe/
    - agent_band: agent-aware
      agent_readiness: 20.7
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 28.8
      mcp:
        status: none
      name: Quaderno
      slug: quaderno
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Invoicing
      - Sales Tax
      - Tax Compliance
      - VAT
      tier: declared
      url: /providers/quaderno/
  - capability:
      attribution: Turbo EA
      id: BC-600.60.50
      key: BC-600.60.50
      name: Integration and API Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 31.1
      apps:
      - Canvas LMS
      band: strong
      in_catalog: true
      kin_score: 59.8
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SQS
      slug: amazon-sqs
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Amazon Web Services
      - Cloud
      - Distributed Systems
      - Messaging
      tier: observed
      url: /providers/amazon-sqs/
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Canvas LMS
      band: developing
      in_catalog: true
      kin_score: 49.3
      mcp:
        status: none
      name: Amazon Kinesis
      slug: kinesis
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Apache Flink
      - Big Data
      tier: observed
      url: /providers/kinesis/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 24.7
      apps:
      - Udemy
      band: emerging
      in_catalog: true
      kin_score: 23.0
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
    - agent_band: null
      agent_readiness: null
      apps:
      - Coursera
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Kochava
      slug: kochava
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/org.coursera.android/latest/
      status: queued for profiling
      tags: []
      tier: observed
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-150.30
      key: AE-150.30
      name: Push Notifications
      url: /capabilities/push-notifications/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Canvas LMS
      band: strong
      in_catalog: true
      kin_score: 55.5
      mcp: &id009
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags: &id010
      - Amazon Web Services
      - Email
      - Messaging
      - Notification
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: agent-aware
      agent_readiness: 14.2
      apps:
      - Open edX
      band: developing
      in_catalog: true
      kin_score: 50.3
      mcp: *id007
      name: Firebase
      slug: firebase
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/firebase/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.10
      key: AE-150.20.10
      name: SMS
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.4
      apps:
      - Moodle
      band: strong
      in_catalog: true
      kin_score: 55.5
      mcp: *id009
      name: Amazon SNS
      slug: amazon-sns
      sources:
      - https://github.com/moodle/moodle/tree/main/public/sms/gateway
      status: profiled
      tags: *id010
      tier: observed
      url: /providers/amazon-sns/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Moodle
      band: minimal
      in_catalog: true
      kin_score: 8.0
      mcp:
        status: unknown
      name: Modica
      slug: modica
      sources:
      - https://github.com/moodle/moodle/tree/main/public/sms/gateway
      status: profiled
      tags:
      - CPaaS
      - Communications
      - Enterprise
      - Messaging
      tier: observed
      url: /providers/modica/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.20.10
      key: AE-120.20.10
      name: Base Map Tiles
      url: /capabilities/maps-tiles/
      via_parent: Maps & Tiles
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.0
      apps:
      - Chamilo
      band: exemplar
      in_catalog: true
      kin_score: 71.4
      mcp:
        source: https://developers.google.com/maps/ai/grounding-lite
        status: verified
      name: Google Maps
      slug: google-maps
      sources:
      - https://github.com/chamilo/chamilo-lms/blob/master/composer.json
      status: profiled
      tags:
      - Environment
      - Geocoding
      - Geolocation
      - Maps
      tier: observed
      url: /providers/google-maps/
  - capability:
      attribution: Turbo EA
      id: BC-3780
      key: content-compliance-standards-management
      name: Content Compliance & Standards Management
      url: /capabilities/content-compliance-standards-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.2
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 56.7
      mcp:
        source: https://www.npmjs.com/package/accessflow-mcp-server
        status: verified
      name: accessiBe
      slug: accessibe
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Accessibility
      - Company
      - WCAG
      - Web Accessibility
      tier: declared
      url: /providers/accessibe/
  - capability:
      attribution: Turbo EA
      id: BC-420.10
      key: customer-data-management
      name: Customer Data Management
      url: /capabilities/customer-data-management/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 26.8
      apps:
      - Open edX
      band: developing
      in_catalog: true
      kin_score: 43.8
      mcp:
        status: none
      name: Segment
      slug: segment
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      status: profiled
      tags:
      - CDP
      - Company
      - Customer Data Platform
      - Identity Resolution
      tier: observed
      url: /providers/segment/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 41.2
      apps:
      - Thinkific
      band: strong
      in_catalog: true
      kin_score: 61.1
      mcp:
        source: https://github.com/intuit/quickbooks-online-mcp-server
        status: verified
      name: QuickBooks Sync
      slug: quickbooks
      sources:
      - https://www.thinkific.com/app-store/
      status: profiled
      tags:
      - Accounting
      - Bookkeeping
      - Finance
      - Small Business
      tier: declared
      url: /providers/quickbooks/
  - capability:
      attribution: API Evangelist extension
      id: AE-120.50.10
      key: AE-120.50.10
      name: IP Geolocation
      url: /capabilities/device-ip-location/
      via_parent: Device & IP Location
    providers:
    - agent_band: agent-aware
      agent_readiness: 17.9
      apps:
      - Open edX
      band: thin
      in_catalog: true
      kin_score: 33.3
      mcp:
        status: none
      name: MaxMind
      slug: maxmind
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
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
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.0
      apps:
      - Udemy
      band: strong
      in_catalog: true
      kin_score: 61.5
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.udemy.android/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: Turbo EA
      id: BC-610
      key: information-data-management
      name: Information & Data Management
      url: /capabilities/information-data-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 45.8
      apps:
      - Open edX
      band: exemplar
      in_catalog: true
      kin_score: 81.1
      mcp:
        source: https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp
        status: verified
      name: Snowflake
      slug: snowflake
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      status: profiled
      tags:
      - Data
      - Data Lakehouse
      - Data Warehouse
      - Snowflake
      tier: observed
      url: /providers/snowflake/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.9
      apps:
      - LearnWorlds
      band: thin
      in_catalog: true
      kin_score: 33.0
      mcp:
        status: none
      name: Weglot
      slug: weglot
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Internationalization
      - Localization
      - Machine Translation
      - Translation
      tier: declared
      url: /providers/weglot/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-native
      agent_readiness: 41.9
      apps:
      - Canvas LMS
      band: exemplar
      in_catalog: true
      kin_score: 80.9
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon DynamoDB
      slug: amazon-dynamodb
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      status: profiled
      tags:
      - Amazon Web Services
      - Database
      - Document Store
      - Key-Value Store
      tier: observed
      url: /providers/amazon-dynamodb/
  - capability:
      attribution: Turbo EA
      id: BC-4280
      key: product-telemetry-experimentation-management
      name: Product Telemetry & Experimentation Management
      url: /capabilities/product-telemetry-experimentation-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.9
      apps:
      - Open edX
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        source: https://support.optimizely.com/hc/en-us/articles/45320607594893
        status: documented
      name: Optimizely
      slug: optimizely
      sources:
      - https://github.com/openedx/edx-platform/blob/master/requirements/edx/base.txt
      status: profiled
      tags:
      - A/B Testing
      - Content Management
      - Customer Data
      - E-Commerce
      tier: observed
      url: /providers/optimizely/
  - capability:
      attribution: Turbo EA
      id: BC-2800.10
      key: scheduling-appointment-management
      name: Scheduling & Appointment Management
      url: /capabilities/scheduling-appointment-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.1
      apps:
      - LearnWorlds
      band: developing
      in_catalog: true
      kin_score: 45.0
      mcp:
        source: https://developer.calendly.com/calendly-mcp-server
        status: documented
      name: Calendly
      slug: calendly
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Appointments
      - Automation
      - Booking
      - Calendar
      tier: declared
      url: /providers/calendly/
  - capability:
      attribution: API Evangelist extension
      id: AE-911
      key: AE-911
      name: Tag Management
      url: /capabilities/product-telemetry-instrumentation/
      via_parent: Product Telemetry Instrumentation
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.2
      apps:
      - LearnWorlds
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google Tag Manager
      slug: google-tag-manager
      sources:
      - https://www.learnworlds.com/integrations/
      status: profiled
      tags:
      - Analytics
      - Conversion Tracking
      - Marketing
      - Tag Management
      tier: declared
      url: /providers/google-tag-manager/
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
      agent_readiness: 35.8
      apps:
      - Canvas LMS
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 51.4
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS Bedrock
      slug: amazon-bedrock
      sources:
      - https://github.com/instructure/canvas-lms/blob/master/Gemfile.d/app.rb
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - Amazon Web Services
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/amazon-bedrock/
    - agent_band: agent-ready
      agent_readiness: 47.6
      apps:
      - Moodle
      band: exemplar
      in_catalog: true
      kin_score: 87.5
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 58.4
      apps:
      - Moodle
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - Moodle
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        status: none
      name: Gemini
      slug: google-gemini
      sources:
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
    - agent_band: agent-aware
      agent_readiness: 23.7
      apps:
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        source: https://github.com/microsoft-foundry/mcp-foundry
        status: verified
      name: Azure AI
      slug: azure-ai-foundry
      sources:
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Foundation Models
      - Generative AI
      tier: observed
      url: /providers/azure-ai-foundry/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - Moodle
      band: developing
      in_catalog: true
      kin_score: 43.3
      mcp:
        status: none
      name: DeepSeek
      slug: deepseek
      sources:
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - Artificial Intelligence
      - Chat
      - Chat Completions
      - LLM
      tier: observed
      url: /providers/deepseek/
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
      - Moodle
      band: thin
      in_catalog: true
      kin_score: 38.0
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/moodle/moodle/tree/main/public/ai/provider
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
  layer: agent
summary:
  coverage_pct: 94.8
  declared_only: 55
  distinct_providers: 116
  in_catalog: 110
  mcp:
    documented: 7
    none: 57
    unchecked: 6
    verified: 41
  mcp_verified: 41
  mean_kin_score: 51.6
  observed: 61
  queued: 6
  reference_apps: 8
title: 'Online Courses & Learning Management: application blueprint'
---
