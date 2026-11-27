---
access: understanding
agent_layer:
- app: Tolgee
  finding: ships an MCP registry server.json at the repo root (own MCP server)
  source: https://github.com/tolgee/tolgee-platform/blob/main/server.json
  tier: observed
- app: DeepL
  finding: DeepL offered inside ChatGPT and Claude; first-party DeepL MCP server per mcp-registry
  source: https://www.deepl.com/en/integrations
  tier: declared
apps:
- anchor: weblate
  counts:
    declared: 0
    observed: 33
  evidence:
  - route: dependency manifest
    url: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
  - route: source code
    url: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
  - route: source code
    url: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Alibaba Cloud Machine Translation
    provider: alibabacloud
    says: ships the Alibaba Cloud Machine Translation SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
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
    name: Amazon Translate
    provider: amazon-translate
    says: ships the Amazon Translate SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Anthropic
    provider: anthropic
    says: ships the Anthropic SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: Apertium
    provider: apertium
    says: ships the Apertium SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: Azure AI Translator
    provider: microsoft-cognitive-services
    says: ships the Azure AI Translator SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure DevOps
    provider: microsoft-azure-devops
    says: ships the Azure DevOps SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: ships the Azure OpenAI SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/machinery/openai.py
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
    name: Baidu Translate
    provider: baidu
    says: ships the Baidu Translate SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: ships the Bitbucket SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
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
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: European Commission eTranslation
    provider: european-commission-etranslation
    says: ships the European Commission eTranslation SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gerrit Code Review
    provider: gerrit
    says: ships the Gerrit Code Review SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Gitea
    provider: gitea
    says: ships the Gitea SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: ships the GitHub SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.30
      key: AE-110.40.30
      name: Translation Memory & Terminology Lookup
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Glosbe
    provider: glosbe
    says: ships the Glosbe SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: Google Cloud Error Reporting
    provider: google-cloud-error-reporting
    says: ships the Google Cloud Error Reporting SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
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
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: ships the Google Cloud Storage SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
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
    name: Google Cloud Translation
    provider: google-translate
    says: ships the Google Cloud Translation SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Mistral AI
    provider: mistral
    says: ships the Mistral AI SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: ModernMT
    provider: modernmt
    says: ships the ModernMT SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.30
      key: AE-110.40.30
      name: Translation Memory & Terminology Lookup
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: MyMemory (Translated)
    provider: mymemory
    says: ships the MyMemory (Translated) SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: NetEase Youdao
    provider: youdao
    says: ships the NetEase Youdao SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Pagure
    provider: pagure
    says: ships the Pagure SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
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
    name: Rollbar
    provider: rollbar
    says: ships the Rollbar SDK or integration code
    source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
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
    name: SAP Translation Hub
    provider: sap-btp
    says: ships the SAP Translation Hub SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    source: https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
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
    name: SYSTRAN
    provider: systran
    says: ships the SYSTRAN SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
    name: Yandex Translate
    provider: yandex-translate
    says: ships the Yandex Translate SDK or integration code
    source: https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
    tier: observed
  kind: self-hosted
  name: Weblate
  page: /applications/translation/weblate/
  slug: weblate
  url: https://github.com/WeblateOrg/weblate
- anchor: tolgee
  counts:
    declared: 0
    observed: 17
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
    layer: common
    name: Slack
    provider: slack
    says: ships the Slack SDK or integration code
    source: https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
    tier: observed
  kind: self-hosted
  name: Tolgee
  page: /applications/translation/tolgee/
  slug: tolgee
  url: https://github.com/tolgee/tolgee-platform
- anchor: pontoon
  counts:
    declared: 0
    observed: 13
  evidence:
  - route: dependency manifest
    url: https://github.com/mozilla/pontoon/blob/main/requirements/1-prod.in
  - route: source code
    url: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
  - route: source code
    url: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Caighdean (cadhan.com)
    provider: caighdean
    says: ships the Caighdean (cadhan.com) SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
    name: GitLab
    provider: gitlab
    says: ships the GitLab SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
    tier: observed
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
    says: ships the Google Analytics SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
    name: Google Cloud AutoML Translation
    provider: google-cloud-automl
    says: ships the Google Cloud AutoML Translation SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
    name: Google Cloud Translation
    provider: google-translate
    says: ships the Google Cloud Translation SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.30
      key: AE-110.40.30
      name: Translation Memory & Terminology Lookup
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Microsoft Terminology Service
    provider: microsoft-terminology
    says: ships the Microsoft Terminology Service SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    name: Microsoft Translator
    provider: microsoft-cognitive-services
    says: ships the Microsoft Translator SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    name: Mozilla accounts
    provider: mozilla-accounts
    says: ships the Mozilla accounts SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
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
    name: New Relic
    provider: new-relic
    says: ships the New Relic SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/requirements/1-prod.in
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: ships the OpenAI SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
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
    name: SendGrid
    provider: sendgrid
    says: ships the SendGrid SDK or integration code
    source: https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
    tier: observed
  kind: self-hosted
  name: Pontoon
  page: /applications/translation/pontoon/
  slug: pontoon
  url: https://github.com/mozilla/pontoon
- anchor: libretranslate
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/LibreTranslate/LibreTranslate/blob/main/pyproject.toml
  integrations: []
  kind: self-hosted
  name: LibreTranslate
  page: /applications/translation/libretranslate/
  slug: libretranslate
  url: https://github.com/LibreTranslate/LibreTranslate
- anchor: lokalise
  counts:
    declared: 32
    observed: 0
  evidence:
  - route: integrations page
    url: https://lokalise.com/integrations
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
    says: lists Amazon S3 as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Asana
    provider: asana
    says: lists Asana as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Azure Repos
    provider: microsoft-azure-devops
    says: lists Azure Repos as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: Bitbucket
    provider: bitbucket
    says: lists Bitbucket as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Braze
    provider: braze
    says: lists Braze as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contentful
    provider: contentful
    says: lists Contentful as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contentstack
    provider: contentstack
    says: lists Contentstack as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Customer.io
    provider: customer-io
    says: lists Customer.io as an integration
    source: https://lokalise.com/integrations
    tier: declared
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
    says: lists Datadog as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Ditto (dittowords.com)
    provider: dittowords
    says: lists Ditto (dittowords.com) as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitLab
    provider: gitlab
    says: lists GitLab as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: common
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot
    provider: hubspot
    says: lists HubSpot as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Hygraph
    provider: hygraph
    says: lists Hygraph as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom Articles
    provider: intercom
    says: lists Intercom Articles as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: Iterable
    provider: iterable
    says: lists Iterable as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Jira
    provider: jira
    says: lists Jira as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: Mailchimp
    provider: mailchimp
    says: lists Mailchimp as an integration
    source: https://lokalise.com/integrations
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
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    credit: null
    layer: domain
    name: MoEngage
    provider: moengage
    says: lists MoEngage as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    credit: null
    layer: domain
    name: Salesforce CRM / Knowledge
    provider: salesforce
    says: lists Salesforce CRM / Knowledge as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Sketch
    provider: sketch
    says: lists Sketch as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Storyblok
    provider: storyblok
    says: lists Storyblok as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: TimeCamp
    provider: timecamp
    says: lists TimeCamp as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    credit: null
    layer: common
    name: Trello
    provider: trello
    says: lists Trello as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: WordPress
    provider: wordpress
    says: lists WordPress as an integration
    source: https://lokalise.com/integrations
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
    source: https://lokalise.com/integrations
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk Guide
    provider: zendesk
    says: lists Zendesk Guide as an integration
    source: https://lokalise.com/integrations
    tier: declared
  kind: commercial
  name: Lokalise
  page: /applications/translation/lokalise/
  slug: lokalise
  url: https://lokalise.com/
- anchor: crowdin
  counts:
    declared: 11
    observed: 0
  evidence:
  - route: integrations page
    url: https://store.crowdin.com/
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Adobe Experience Manager
    provider: adobe-experience-manager
    says: lists Adobe Experience Manager as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Contentful
    provider: contentful
    says: lists Contentful as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    credit: null
    layer: domain
    name: Figma
    provider: figma
    says: lists Figma as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    credit: null
    layer: domain
    name: GitHub
    provider: github
    says: lists GitHub as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    credit: null
    layer: domain
    name: HubSpot Marketing Hub
    provider: hubspot
    says: lists HubSpot Marketing Hub as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Intercom
    provider: intercom
    says: lists Intercom as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Opal by Welocalize
    provider: welocalize
    says: lists Opal by Welocalize as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenAI
    provider: openai
    says: lists OpenAI as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    credit: null
    layer: common
    name: Slack
    provider: slack
    says: lists Slack as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    credit: null
    layer: domain
    name: Webflow
    provider: webflow
    says: lists Webflow as an integration
    source: https://store.crowdin.com/
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    credit: null
    layer: domain
    name: Zendesk Guide
    provider: zendesk
    says: lists Zendesk Guide as an integration
    source: https://store.crowdin.com/
    tier: declared
  kind: commercial
  name: Crowdin
  page: /applications/translation/crowdin/
  slug: crowdin
  url: https://crowdin.com/
- anchor: deepl
  counts:
    declared: 8
    observed: 1
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.deepl.mobiletranslator/latest/
  - route: integrations page
    url: https://www.deepl.com/en/integrations
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: Exodus Privacy (reports.exodus-privacy.eu.org)
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.deepl.mobiletranslator/latest/
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10
      key: AE-250.10
      name: Package Registries & Distribution
      url: /capabilities/package-registries-distribution/
      via_parent: null
    credit: null
    layer: common
    name: AWS Marketplace
    provider: amazon-web-services
    says: lists AWS Marketplace as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: ChatGPT
    provider: openai
    says: lists ChatGPT as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    credit: null
    layer: agent
    name: Claude
    provider: anthropic
    says: lists Claude as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Google Workspace
    provider: google-workspace
    says: lists Google Workspace as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: LinkedIn
    provider: linkedin
    says: lists LinkedIn as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Microsoft 365 (Word, Outlook, PowerPoint)
    provider: microsoft-365
    says: lists Microsoft 365 (Word, Outlook, PowerPoint) as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: WhatsApp
    provider: whatsapp
    says: lists WhatsApp as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: X (Twitter)
    provider: x
    says: lists X (Twitter) as an integration
    source: https://www.deepl.com/en/integrations
    tier: declared
  kind: commercial
  name: DeepL
  page: /applications/translation/deepl/
  slug: deepl
  url: https://www.deepl.com/
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: translation
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Reference
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: Books & Reference
  store: google-play
  url: https://play.google.com/store/apps/category/BOOKS_AND_REFERENCE
- category: Software Development - Localization
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#software-development---localization
- category: Store design
  store: shopify-app-store
  url: https://apps.shopify.com/categories
- category: Translation
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
name: Translation & Localization
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: every TMS plugs in MT engines (DeepL, Google, Amazon, Azure, Yandex, Baidu, ...); the category is built on them
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: LLM translation (OpenAI, Azure OpenAI, Anthropic, Mistral, Gemini, Ollama) now ships next to classic MT
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.30
    key: AE-110.40.30
    name: Translation Memory & Terminology Lookup
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: public translation-memory and terminology lookups (MyMemory, Glosbe, Microsoft Terminology); no node exists
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  fit: exact
  layer: domain
  why: continuous localization syncs resource files with git hosts and opens pull/merge requests
- capability:
    attribution: API Evangelist extension
    id: AE-170.70
    key: AE-170.70
    name: Content Management
    url: /capabilities/content-management/
    via_parent: null
  fit: exact
  layer: domain
  why: CMS connectors push content out for translation and back
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  fit: exact
  layer: domain
  why: design-tool plugins (Figma, Sketch) localize UI copy before code
- capability:
    attribution: Turbo EA
    id: BC-4260.40
    key: customer-lifecycle-engagement
    name: Customer Lifecycle Engagement
    url: /capabilities/customer-lifecycle-engagement/
    via_parent: null
  fit: exact
  layer: domain
  why: localized campaign/message content (Braze, Iterable, Customer.io, MoEngage)
- capability:
    attribution: Turbo EA
    id: BC-430
    key: customer-service-management
    name: Customer Service Management
    url: /capabilities/customer-service-management/
    via_parent: null
  fit: exact
  layer: domain
  why: help-center article translation (Zendesk Guide, Intercom Articles)
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: domain
  why: Salesforce / HubSpot content localization
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: community translation platforms sign volunteers in with GitHub/GitLab/Google/Mozilla
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: file/screenshot storage and bucket sync
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error tracking / APM
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: notifications
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: PostHog, Google Analytics
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: common
  why: Zapier / Make connectors
- capability:
    attribution: API Evangelist extension
    id: AE-100.10
    key: AE-100.10
    name: Agent Tool Exposure
    url: /capabilities/agent-tool-exposure/
    via_parent: null
  fit: exact
  layer: agent
  why: MT vendors now ship inside assistants (DeepL in ChatGPT/Claude)
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.10
      key: AE-110.40.10
      name: Machine Translation
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.9
      apps:
      - Pontoon
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: Google Cloud Translation
      slug: google-translate
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
      status: profiled
      tags:
      - Google Cloud
      - Internationalization
      - Language Detection
      - Localization
      tier: observed
      url: /providers/google-translate/
    - agent_band: agent-ready
      agent_readiness: 32.2
      apps:
      - Pontoon
      - Tolgee
      - Weblate
      band: strong
      in_catalog: true
      kin_score: 62.4
      mcp:
        source: https://github.com/microsoft/azure-speech-mcp-server
        status: verified
      name: Azure AI Translator
      slug: microsoft-cognitive-services
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
      status: profiled
      tags:
      - Azure AI
      - Computer Vision
      - Natural Language Processing
      - Speech
      tier: observed
      url: /providers/microsoft-cognitive-services/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 73.7
      mcp:
        source: https://api.github.com/repos/awslabs/mcp/contents/src
        status: verified
      name: Amazon Translate
      slug: amazon-translate
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
      status: profiled
      tags:
      - Amazon Web Services
      - Language Processing
      - Localization
      - Machine Translation
      tier: observed
      url: /providers/amazon-translate/
    - agent_band: agent-ready
      agent_readiness: 36.1
      apps:
      - Tolgee
      - Weblate
      band: strong
      in_catalog: true
      kin_score: 61.4
      mcp:
        source: https://github.com/DeepL/deepl-mcp-server
        status: verified
      name: DeepL
      slug: deepl
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
      status: profiled
      tags:
      - Artificial Intelligence
      - Deep Learning
      - Glossary
      - Localization
      tier: observed
      url: /providers/deepl/
    - agent_band: agent-aware
      agent_readiness: 5.8
      apps:
      - Tolgee
      - Weblate
      band: emerging
      in_catalog: true
      kin_score: 17.4
      mcp:
        source: https://github.com/baidu-maps/mcp
        status: verified
      name: Baidu Translate
      slug: baidu
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/constants/MtServiceType.kt
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Machine Learning
      - Technology
      tier: observed
      url: /providers/baidu/
    - agent_band: agent-ready
      agent_readiness: 42.2
      apps:
      - Pontoon
      band: strong
      in_catalog: true
      kin_score: 63.2
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud AutoML Translation
      slug: google-vertex-ai
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - Google Cloud
      - Machine Learning
      tier: observed
      url: /providers/google-vertex-ai/
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Weblate
      band: developing
      in_catalog: true
      kin_score: 39.3
      mcp:
        status: unknown
      name: ModernMT
      slug: modernmt
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Multilingual
      - Translation
      tier: observed
      url: /providers/modernmt/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Weblate
      band: thin
      in_catalog: true
      kin_score: 36.5
      mcp:
        status: none
      name: Yandex Translate
      slug: yandex-translate
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Language Detection
      - Machine Translation
      - Natural Language Processing
      - Translation Dictionary
      tier: observed
      url: /providers/yandex-translate/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - Weblate
      band: emerging
      in_catalog: true
      kin_score: 25.5
      mcp:
        status: none
      name: SYSTRAN
      slug: systran
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Neural Machine Translation
      - Translation
      tier: observed
      url: /providers/systran/
    - agent_band: agent-aware
      agent_readiness: 23.3
      apps:
      - Weblate
      band: emerging
      in_catalog: true
      kin_score: 24.3
      mcp:
        source: https://github.com/LibreTranslate/LibreTranslate-MCP
        status: verified
      name: LibreTranslate
      slug: libre-translate
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Machine Translation
      - Natural Language Processing
      - Open Source
      - Translation
      tier: observed
      url: /providers/libre-translate/
    - agent_band: agent-aware
      agent_readiness: 13.3
      apps:
      - Weblate
      band: emerging
      in_catalog: true
      kin_score: 22.7
      mcp:
        status: none
      name: SAP Translation Hub
      slug: sap-btp
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Artificial Intelligence
      - Cloud Platform
      - Integration
      - SAP
      tier: observed
      url: /providers/sap-btp/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Weblate
      band: emerging
      in_catalog: true
      kin_score: 16.2
      mcp:
        status: unknown
      name: European Commission eTranslation
      slug: european-commission-etranslation
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Government
      - Translation
      tier: observed
      url: /providers/european-commission-etranslation/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Pontoon
      band: minimal
      in_catalog: true
      kin_score: 5.0
      mcp:
        status: unknown
      name: Caighdean (cadhan.com)
      slug: caighdean
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
      status: profiled
      tags:
      - Company
      - Irish
      - Language
      - Open Source
      tier: observed
      url: /providers/caighdean/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 4.7
      mcp:
        status: none
      name: Apertium
      slug: apertium
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Linguistics
      - Machine Translation
      - Natural Language Processing
      - Open Source
      tier: observed
      url: /providers/apertium/
    - agent_band: agent-aware
      agent_readiness: 10.6
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 4.3
      mcp:
        status: unknown
      name: NetEase Youdao
      slug: youdao
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Education
      - Language
      tier: observed
      url: /providers/youdao/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        source: https://github.com/aliyun/alibaba-cloud-ops-mcp-server
        status: verified
      name: Alibaba Cloud Machine Translation
      slug: alibabacloud
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/alibabacloud/
    - agent_band: agent-ready
      agent_readiness: 46.5
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 77.8
      mcp:
        status: none
      name: LinkedIn
      slug: linkedin
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags:
      - Business
      - Careers
      - LinkedIn
      - Marketing
      tier: declared
      url: /providers/linkedin/
    - agent_band: agent-native
      agent_readiness: 59.9
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 75.0
      mcp:
        source: https://github.com/xdevplatform/xmcp
        status: verified
      name: X (Twitter)
      slug: x
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags:
      - Conversations
      - Social
      - Spaces
      - X
      tier: declared
      url: /providers/x/
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 72.3
      mcp:
        status: none
      name: WhatsApp
      slug: whatsapp
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags:
      - Analytics
      - Business Messaging
      - Messaging
      - WhatsApp
      tier: declared
      url: /providers/whatsapp/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Crowdin
      band: emerging
      in_catalog: true
      kin_score: 11.0
      mcp:
        status: none
      name: Opal by Welocalize
      slug: welocalize
      sources:
      - https://store.crowdin.com/
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Localization
      - Translation
      tier: declared
      url: /providers/welocalize/
  - capability:
      attribution: Turbo EA
      id: BC-4200.40
      key: software-construction-management
      name: Software Construction Management
      url: /capabilities/software-construction-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Crowdin
      - Lokalise
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: &id005
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub
      slug: github
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags: &id006
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: observed
      url: /providers/github/
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Lokalise
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: &id003
        source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
        status: verified
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      - https://lokalise.com/integrations
      status: profiled
      tags: &id004
      - Code
      - Developer Tools
      - Platform
      - Software Development
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 37.7
      apps:
      - Lokalise
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 81.9
      mcp:
        source: https://github.com/microsoft/azure-devops-mcp
        status: verified
      name: Azure DevOps
      slug: microsoft-azure-devops
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Agile
      - CI/CD
      - DevOps
      - Developer Tools
      tier: observed
      url: /providers/microsoft-azure-devops/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Lokalise
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 71.9
      mcp:
        source: https://github.com/atlassian/atlassian-mcp-server
        status: verified
      name: Bitbucket
      slug: bitbucket
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Atlassian
      - CI/CD
      - Code Collaboration
      - Code Review
      tier: observed
      url: /providers/bitbucket/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        source: https://gitea.com/gitea/gitea-mcp
        status: verified
      name: Gitea
      slug: gitea
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      status: profiled
      tags:
      - CI/CD
      - DevOps
      - Gitea
      - Version Control
      tier: observed
      url: /providers/gitea/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 7.9
      mcp:
        status: none
      name: Pagure
      slug: pagure
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      status: profiled
      tags:
      - Code Hosting
      - Fedora
      - Open Source
      - Version Control
      tier: observed
      url: /providers/pagure/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 6.8
      mcp:
        source: https://github.com/GerritCodeReview/gerrit-mcp-server
        status: verified
      name: Gerrit Code Review
      slug: gerrit
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/vcs/git.py
      status: profiled
      tags:
      - Code Review
      - Company
      - Open Source
      - Version Control
      tier: observed
      url: /providers/gerrit/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.10
      key: AE-110.10.10
      name: Hosted LLM Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - Crowdin
      - Pontoon
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: &id011
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
      status: profiled
      tags: &id012
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp: &id009
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
      status: profiled
      tags: &id010
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/weblate/machinery/openai.py
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: observed
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Tolgee
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google AI (Gemini)
      slug: google-gemini
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/src/main/kotlin/io/tolgee/model/enums/LlmProviderType.kt
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
      - Weblate
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: observed
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 24.4
      apps:
      - Weblate
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
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
      id: AE-170.70
      key: AE-170.70
      name: Content Management
      url: /capabilities/content-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 62.5
      apps:
      - Crowdin
      - Lokalise
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        source: https://developers.webflow.com/mcp/reference/overview
        status: verified
      name: Webflow
      slug: webflow
      sources:
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags:
      - CMS
      - E-Commerce
      - No-Code
      - Web Development
      tier: declared
      url: /providers/webflow/
    - agent_band: agent-ready
      agent_readiness: 55.2
      apps:
      - Crowdin
      - Lokalise
      band: developing
      in_catalog: true
      kin_score: 43.9
      mcp:
        source: https://github.com/contentful/contentful-mcp-server
        status: verified
      name: Contentful
      slug: contentful
      sources:
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags:
      - CMS
      - Content
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/contentful/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 73.6
      mcp:
        source: https://registry.npmjs.org/@contentstack/mcp
        status: verified
      name: Contentstack
      slug: contentstack
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Content Delivery
      - Content Management
      - Digital Experience
      - Headless CMS
      tier: declared
      url: /providers/contentstack/
    - agent_band: agent-ready
      agent_readiness: 38.0
      apps:
      - Lokalise
      band: strong
      in_catalog: true
      kin_score: 55.1
      mcp:
        source: https://github.com/storyblok/mcp-server
        status: verified
      name: Storyblok
      slug: storyblok
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Delivery
      - Content Management
      - Headless CMS
      tier: declared
      url: /providers/storyblok/
    - agent_band: agent-ready
      agent_readiness: 31.9
      apps:
      - Lokalise
      band: developing
      in_catalog: true
      kin_score: 46.6
      mcp:
        source: https://github.com/WordPress/mcp-adapter
        status: verified
      name: WordPress
      slug: wordpress
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - CMS
      - Content Management
      - Open Source
      - WordPress
      tier: declared
      url: /providers/wordpress/
    - agent_band: agent-aware
      agent_readiness: 21.4
      apps:
      - Crowdin
      band: thin
      in_catalog: true
      kin_score: 28.0
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Manager
      slug: adobe-experience-manager
      sources:
      - https://store.crowdin.com/
      status: profiled
      tags:
      - Content Management
      - Digital Asset Management
      - Enterprise CMS
      - Headless CMS
      tier: declared
      url: /providers/adobe-experience-manager/
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Lokalise
      band: emerging
      in_catalog: true
      kin_score: 21.7
      mcp:
        status: none
      name: Hygraph
      slug: hygraph
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Content Federation
      - Content Management
      - GraphQL
      - Headless CMS
      tier: declared
      url: /providers/hygraph/
  - capability:
      attribution: Turbo EA
      id: BC-4260.40
      key: customer-lifecycle-engagement
      name: Customer Lifecycle Engagement
      url: /capabilities/customer-lifecycle-engagement/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 70.1
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 85.9
      mcp:
        source: https://github.com/customerio/claude-plugin
        status: verified
      name: Customer.io
      slug: customer-io
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Behavioral Data
      - Broadcast
      - CDP
      - Campaigns
      tier: declared
      url: /providers/customer-io/
    - agent_band: agent-ready
      agent_readiness: 58.4
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://www.braze.com/docs/user_guide/brazeai/mcp_server
        status: verified
      name: Braze
      slug: braze
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Customer Engagement
      - Marketing Automation
      - Messaging
      - Push Notifications
      tier: declared
      url: /providers/braze/
    - agent_band: agent-ready
      agent_readiness: 33.8
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/Iterable/mcp-server
        status: verified
      name: Iterable
      slug: iterable
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Cross-Channel Messaging
      - Customer Engagement
      - Email
      - Marketing Automation
      tier: declared
      url: /providers/iterable/
    - agent_band: agent-native
      agent_readiness: 65.1
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 68.0
      mcp:
        status: none
      name: MoEngage
      slug: moengage
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Customer Data Platform
      - Customer Engagement
      - Marketing Automation
      - Push Notifications
      tier: declared
      url: /providers/moengage/
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
      - Crowdin
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 72.4
      mcp:
        status: none
      name: Zendesk Guide
      slug: zendesk
      sources:
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags:
      - CRM
      - Chat
      - Help Center
      - Sell
      tier: declared
      url: /providers/zendesk/
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Crowdin
      - Lokalise
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp: &id007
        source: https://developers.intercom.com/docs/guides/mcp
        status: verified
      name: Intercom Articles
      slug: intercom
      sources:
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags: &id008
      - Artificial Intelligence
      - Conversational AI
      - Customer Service
      - Messaging
      tier: declared
      url: /providers/intercom/
  - capability:
      attribution: API Evangelist extension
      id: AE-170.80
      key: AE-170.80
      name: Design & Creative Editing
      url: /capabilities/design-creative-editing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 59.2
      apps:
      - Crowdin
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 75.1
      mcp:
        source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
        status: verified
      name: Figma
      slug: figma
      sources:
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags:
      - Collaboration
      - Design
      - Graphics
      - Interfaces
      tier: declared
      url: /providers/figma/
    - agent_band: agent-ready
      agent_readiness: 41.7
      apps:
      - Lokalise
      band: developing
      in_catalog: true
      kin_score: 52.8
      mcp:
        source: https://developer.dittowords.com/mcp-reference/overview
        status: verified
      name: Ditto (dittowords.com)
      slug: dittowords
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Content
      - Localization
      tier: declared
      url: /providers/dittowords/
    - agent_band: human-only
      agent_readiness: 3.5
      apps:
      - Lokalise
      band: emerging
      in_catalog: true
      kin_score: 18.0
      mcp:
        source: https://github.com/sketch-hq/sketch-mcp-bundle
        status: verified
      name: Sketch
      slug: sketch
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Design
      - Prototyping
      - Workspace
      tier: declared
      url: /providers/sketch/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.30
      key: AE-110.40.30
      name: Translation Memory & Terminology Lookup
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 10.9
      mcp:
        status: none
      name: MyMemory (Translated)
      slug: mymemory
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Company
      - Localization
      - Machine Translation
      - Translation
      tier: observed
      url: /providers/mymemory/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Weblate
      band: minimal
      in_catalog: true
      kin_score: 7.0
      mcp:
        status: none
      name: Glosbe
      slug: glosbe
      sources:
      - https://github.com/WeblateOrg/weblate/tree/main/weblate/machinery
      status: profiled
      tags:
      - Dictionaries
      - Language Learning
      - Multilingual
      - Translation
      tier: observed
      url: /providers/glosbe/
    - agent_band: null
      agent_readiness: null
      apps:
      - Pontoon
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Microsoft Terminology Service
      slug: microsoft-terminology
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/machinery/views.py
      status: queued for profiling
      tags: []
      tier: observed
      url: null
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
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp: &id001
        source: https://developers.hubspot.com/mcp
        status: verified
      name: HubSpot
      slug: hubspot
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags: &id002
      - Analytics
      - CRM
      - Commerce
      - Content
      tier: declared
      url: /providers/hubspot/
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce CRM / Knowledge
      slug: salesforce
      sources:
      - https://lokalise.com/integrations
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
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365 (Word, Outlook, PowerPoint)
      slug: microsoft-365
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 70.7
      mcp:
        source: https://github.com/gemini-cli-extensions/workspace
        status: verified
      name: Google Workspace
      slug: google-workspace
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/google-workspace/
  - capability:
      attribution: Turbo EA
      id: BC-400.60
      key: digital-marketing-management
      name: Digital Marketing Management
      url: /capabilities/digital-marketing-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 52.0
      apps:
      - Crowdin
      band: exemplar
      in_catalog: true
      kin_score: 91.9
      mcp: *id001
      name: HubSpot Marketing Hub
      slug: hubspot
      sources:
      - https://store.crowdin.com/
      status: profiled
      tags: *id002
      tier: declared
      url: /providers/hubspot/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.20
      key: AE-150.10.20
      name: Email Marketing Sends
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 41.9
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 77.7
      mcp:
        status: none
      name: Mailchimp
      slug: mailchimp
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Campaigns
      - Email Marketing
      - Marketing Automation
      - Newsletters
      tier: declared
      url: /providers/mailchimp/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - DeepL
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/app/build.gradle
      - https://reports.exodus-privacy.eu.org/en/reports/com.deepl.mobiletranslator/latest/
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Pontoon
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.newrelic.com/docs/agentic-ai/mcp/overview/
        status: verified
      name: New Relic
      slug: new-relic
      sources:
      - https://github.com/mozilla/pontoon/blob/main/requirements/1-prod.in
      status: profiled
      tags:
      - APM
      - Analysis
      - Analytics
      - DevOps
      tier: observed
      url: /providers/new-relic/
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Weblate
      band: strong
      in_catalog: true
      kin_score: 59.9
      mcp:
        status: none
      name: Google Cloud Error Reporting
      slug: google-cloud-error-reporting
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
      status: profiled
      tags:
      - Debugging
      - Developer Tools
      - Error Reporting
      - Errors
      tier: observed
      url: /providers/google-cloud-error-reporting/
    - agent_band: agent-ready
      agent_readiness: 30.2
      apps:
      - Weblate
      band: developing
      in_catalog: true
      kin_score: 48.1
      mcp:
        source: https://github.com/rollbar/rollbar-mcp-server
        status: verified
      name: Rollbar
      slug: rollbar
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
      status: profiled
      tags:
      - Debugging
      - DevOps
      - Error Tracking
      - Monitoring
      tier: observed
      url: /providers/rollbar/
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
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
      - Lokalise
      - Tolgee
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: observed
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Lokalise
      - Weblate
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://github.com/WeblateOrg/weblate/blob/main/pyproject.toml
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: observed
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Tolgee
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure-blob-storage/
  - capability:
      attribution: Turbo EA
      id: BC-900.30
      key: project-management
      name: Project Management
      url: /capabilities/project-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 64.4
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 82.4
      mcp:
        source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
        status: verified
      name: Jira
      slug: jira
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Agile
      - ITSM
      - Issue Tracking
      - Project Management
      tier: declared
      url: /providers/jira/
    - agent_band: agent-ready
      agent_readiness: 30.8
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 74.8
      mcp:
        source: https://github.com/atlassian/trello-mcp-server
        status: verified
      name: Trello
      slug: trello
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Kanban
      - Project Management
      - Task Management
      tier: declared
      url: /providers/trello/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 72.5
      mcp:
        source: https://developers.asana.com/docs/using-asanas-mcp-server
        status: verified
      name: Asana
      slug: asana
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Collaboration
      - Productivity
      - Project
      - Project Management
      tier: declared
      url: /providers/asana/
    - agent_band: agent-ready
      agent_readiness: 49.9
      apps:
      - Lokalise
      band: thin
      in_catalog: true
      kin_score: 31.0
      mcp:
        status: none
      name: TimeCamp
      slug: timecamp
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Attendance
      - Productivity
      - Time Tracking
      - Timesheets
      tier: declared
      url: /providers/timecamp/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-native
      agent_readiness: 54.5
      apps:
      - Pontoon
      band: exemplar
      in_catalog: true
      kin_score: 86.3
      mcp: *id003
      name: GitLab
      slug: gitlab
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags: *id004
      tier: observed
      url: /providers/gitlab/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Pontoon
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp: *id005
      name: GitHub
      slug: github
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags: *id006
      tier: observed
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Pontoon
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google sign-in
      slug: google-identity-platform
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: observed
      url: /providers/google-identity-platform/
    - agent_band: agent-aware
      agent_readiness: 6.3
      apps:
      - Pontoon
      band: emerging
      in_catalog: true
      kin_score: 22.9
      mcp:
        status: none
      name: Mozilla accounts
      slug: mozilla-accounts
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags:
      - Authentication
      - Company
      - Identity
      - Mozilla
      tier: observed
      url: /providers/mozilla-accounts/
  - capability:
      attribution: Turbo EA
      id: BC-850.10
      key: internal-communications-management
      name: Internal Communications Management
      url: /capabilities/internal-communications-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Crowdin
      - Lokalise
      - Tolgee
      band: exemplar
      in_catalog: true
      kin_score: 74.4
      mcp:
        source: https://docs.slack.dev/ai/mcp-server/
        status: verified
      name: Slack
      slug: slack
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
      - https://lokalise.com/integrations
      - https://store.crowdin.com/
      status: profiled
      tags:
      - Bots
      - Chat
      - Collaboration
      - Messaging
      tier: observed
      url: /providers/slack/
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
      - Pontoon
      band: exemplar
      in_catalog: true
      kin_score: 79.7
      mcp:
        source: https://developers.google.com/analytics/devguides/MCP
        status: verified
      name: Google Analytics
      slug: google-analytics
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags:
      - Analytics
      - Data
      - Google
      - Metrics
      tier: observed
      url: /providers/google-analytics/
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Tolgee
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 40.7
      apps:
      - Pontoon
      band: exemplar
      in_catalog: true
      kin_score: 84.0
      mcp:
        status: none
      name: SendGrid
      slug: sendgrid
      sources:
      - https://github.com/mozilla/pontoon/blob/main/pontoon/settings/base.py
      status: profiled
      tags:
      - Email
      - Email API
      - Marketing Email
      - SMTP
      tier: observed
      url: /providers/sendgrid/
    - agent_band: agent-aware
      agent_readiness: 22.9
      apps:
      - Tolgee
      band: developing
      in_catalog: true
      kin_score: 50.5
      mcp:
        source: https://github.com/mailgun/mailjet-mcp-server
        status: verified
      name: Mailjet
      slug: mailjet
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/backend/data/build.gradle
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
      agent_readiness: 66.1
      apps:
      - Lokalise
      band: exemplar
      in_catalog: true
      kin_score: 72.9
      mcp:
        source: https://zapier.com/mcp
        status: verified
      name: Zapier
      slug: zapier
      sources:
      - https://lokalise.com/integrations
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
      - Lokalise
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://lokalise.com/integrations
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.70
      key: AE-160.70
      name: Bot Protection & CAPTCHA
      url: /capabilities/bot-protection-captcha/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.9
      apps:
      - Tolgee
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        status: none
      name: Google reCAPTCHA
      slug: google-recaptcha
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/webapp/package.json
      status: profiled
      tags:
      - Abuse Prevention
      - Bot Detection
      - CAPTCHA
      - Fraud Prevention
      tier: observed
      url: /providers/google-recaptcha/
  - capability:
      attribution: Turbo EA
      id: BC-430
      key: customer-service-management
      name: Customer Service Management
      url: /capabilities/customer-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.5
      apps:
      - Tolgee
      band: developing
      in_catalog: true
      kin_score: 51.0
      mcp: *id007
      name: Intercom
      slug: intercom
      sources:
      - https://github.com/tolgee/tolgee-platform/blob/main/webapp/package.json
      status: profiled
      tags: *id008
      tier: observed
      url: /providers/intercom/
  - capability:
      attribution: API Evangelist extension
      id: AE-250.10
      key: AE-250.10
      name: Package Registries & Distribution
      url: /capabilities/package-registries-distribution/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 68.5
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: AWS Marketplace
      slug: amazon-web-services
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags:
      - Amazon
      - Amazon Web Services
      - Cloud
      - Networks
      tier: declared
      url: /providers/amazon-web-services/
  layer: common
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-100.10
      key: AE-100.10
      name: Agent Tool Exposure
      url: /capabilities/agent-tool-exposure/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp: *id009
      name: Claude
      slug: anthropic
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags: *id010
      tier: declared
      url: /providers/anthropic/
    - agent_band: agent-native
      agent_readiness: 57.5
      apps:
      - DeepL
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp: *id011
      name: ChatGPT
      slug: openai
      sources:
      - https://www.deepl.com/en/integrations
      status: profiled
      tags: *id012
      tier: declared
      url: /providers/openai/
  layer: agent
summary:
  coverage_pct: 98.8
  declared_only: 34
  distinct_providers: 80
  in_catalog: 79
  mcp:
    documented: 0
    none: 24
    unchecked: 1
    verified: 51
  mcp_verified: 51
  mean_kin_score: 55.3
  observed: 46
  queued: 1
  reference_apps: 7
title: 'Translation & Localization: application blueprint'
---
