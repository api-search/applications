---
app: Tolgee
app_slug: tolgee
app_url: https://github.com/tolgee/tolgee-platform
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Azure OpenAI
  - Google AI (Gemini)
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Amazon Translate
  - Azure AI Translator
  - Baidu Translate
  - DeepL
  - Google Cloud Translation
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-430
  key: customer-service-management
  layer: common
  name: Customer Service Management
  providers:
  - Intercom
  url: /capabilities/customer-service-management/
  via_parent: null
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - PostHog
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailjet
  url: /capabilities/email/
  via_parent: Email
category:
  id: translation
  name: Translation & Localization
  url: /applications/translation/
counts:
  declared: 0
  observed: 17
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/tolgee/tolgee-platform/blob/main/backend/app/build.gradle
- route: dependency manifest
  url: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
- route: dependency manifest
  url: https://github.com/tolgee/tolgee-platform/blob/main/webapp/package.json
- route: source code
  url: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
- route: source code
  url: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
- route: source code
  url: https://github.com/tolgee/tolgee-platform/tree/main/ee/backend/app/src/main/kotlin/io/tolgee/ee/service/slackIntegration
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
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
  layer: common
  name: Amazon S3
  provider: amazon-s3
  says: ships the Amazon S3 SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id003
      source: https://api.github.com/repos/awslabs/mcp/contents/src
      status: verified
    slug: amazon-translate
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Language Processing
    - Localization
    - Machine Translation
    url: /providers/amazon-translate/
  layer: domain
  name: Amazon Translate
  provider: amazon-translate
  says: ships the Amazon Translate SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
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
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: domain
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.2
    band: strong
    in_catalog: true
    kin_score: 62.4
    mcp: &id007
      source: https://github.com/microsoft/azure-speech-mcp-server
      status: verified
    slug: microsoft-cognitive-services
    status: profiled
    tags: &id008
    - Azure AI
    - Computer Vision
    - Natural Language Processing
    - Speech
    url: /providers/microsoft-cognitive-services/
  layer: domain
  name: Azure AI Translator
  provider: microsoft-cognitive-services
  says: ships the Azure AI Translator SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
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
    mcp: &id009
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id010
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
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
    mcp: &id011
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: domain
  name: Azure OpenAI
  provider: microsoft-azure-openai
  says: ships the Azure OpenAI SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.8
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id013
      source: https://github.com/baidu-maps/mcp
      status: verified
    slug: baidu
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Company
    - Machine Learning
    - Technology
    url: /providers/baidu/
  layer: domain
  name: Baidu Translate
  provider: baidu
  says: ships the Baidu Translate SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.1
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id015
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
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
    mcp: &id017
      status: none
    slug: google-gemini
    status: profiled
    tags: &id018
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: domain
  name: Google AI (Gemini)
  provider: google-gemini
  says: ships the Google AI (Gemini) SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.9
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id019
      status: none
    slug: google-translate
    status: profiled
    tags: &id020
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: domain
  name: Google Cloud Translation
  provider: google-translate
  says: ships the Google Cloud Translation SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
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
    mcp: &id021
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id022
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/webapp/package.json
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
    agent_readiness: 32.5
    band: developing
    in_catalog: true
    kin_score: 51.0
    mcp: &id023
      source: https://developers.intercom.com/docs/guides/mcp
      status: verified
    slug: intercom
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Conversational AI
    - Customer Service
    - Messaging
    url: /providers/intercom/
  layer: common
  name: Intercom
  provider: intercom
  says: ships the Intercom SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/webapp/package.json
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
    agent_band: agent-aware
    agent_readiness: 22.9
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id025
      source: https://github.com/mailgun/mailjet-mcp-server
      status: verified
    slug: mailjet
    status: profiled
    tags: &id026
    - Email
    - Email Delivery
    - Marketing Email
    - SMTP
    url: /providers/mailjet/
  layer: common
  name: Mailjet
  provider: mailjet
  says: ships the Mailjet SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
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
    mcp: &id027
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: domain
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
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
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id029
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id030
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
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
    mcp: &id031
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id032
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/app/build.gradle
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
    mcp: &id033
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id034
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/translation/tolgee/
providers:
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id003
  name: Amazon Translate
  slug: amazon-translate
  status: profiled
  tags: *id004
  url: /providers/amazon-translate/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: strong
  in_catalog: true
  kin_score: 62.4
  mcp: *id007
  name: Azure AI Translator
  slug: microsoft-cognitive-services
  status: profiled
  tags: *id008
  url: /providers/microsoft-cognitive-services/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id009
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id010
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id011
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id012
  url: /providers/microsoft-azure-openai/
- agent_band: agent-aware
  agent_readiness: 5.8
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id013
  name: Baidu Translate
  slug: baidu
  status: profiled
  tags: *id014
  url: /providers/baidu/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id015
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id016
  url: /providers/deepl/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id017
  name: Google AI (Gemini)
  slug: google-gemini
  status: profiled
  tags: *id018
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id019
  name: Google Cloud Translation
  slug: google-translate
  status: profiled
  tags: *id020
  url: /providers/google-translate/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id021
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id022
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 32.5
  band: developing
  in_catalog: true
  kin_score: 51.0
  mcp: *id023
  name: Intercom
  slug: intercom
  status: profiled
  tags: *id024
  url: /providers/intercom/
- agent_band: agent-aware
  agent_readiness: 22.9
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id025
  name: Mailjet
  slug: mailjet
  status: profiled
  tags: *id026
  url: /providers/mailjet/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id027
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id028
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id029
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id030
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id031
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id032
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id033
  name: Slack
  slug: slack
  status: profiled
  tags: *id034
  url: /providers/slack/
siblings:
- name: Crowdin
  rows: 11
  url: /applications/translation/crowdin/
- name: DeepL
  rows: 9
  url: /applications/translation/deepl/
- name: LibreTranslate
  rows: 0
  url: /applications/translation/libretranslate/
- name: Lokalise
  rows: 32
  url: /applications/translation/lokalise/
- name: Pontoon
  rows: 13
  url: /applications/translation/pontoon/
- name: Weblate
  rows: 33
  url: /applications/translation/weblate/
sitemap: true
title: 'Tolgee: Translation & Localization reference app'
---
