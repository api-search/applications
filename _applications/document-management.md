---
access: understanding
agent_layer: []
apps:
- anchor: paperless-ngx
  counts:
    declared: 2
    observed: 6
  evidence:
  - route: dependency manifest
    url: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
  - route: documentation
    url: https://github.com/paperless-ngx/paperless-ngx/blob/dev/docs/configuration.md
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Apache Tika
    provider: apache-tika
    says: ships the Apache Tika SDK or integration code
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Azure AI Document Intelligence
    provider: microsoft-azure
    says: ships the Azure AI Document Intelligence SDK or integration code
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    credit: null
    layer: domain
    name: Gotenberg
    provider: gotenberg
    says: ships the Gotenberg SDK or integration code
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    credit: null
    layer: domain
    name: Hugging Face
    provider: hugging-face
    says: ships the Hugging Face SDK or integration code
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
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
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Gmail
    provider: google-gmail
    says: lists Gmail as an integration
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/docs/configuration.md
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    credit: null
    layer: common
    name: Outlook
    provider: microsoft-outlook
    says: lists Outlook as an integration
    source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/docs/configuration.md
    tier: declared
  kind: self-hosted
  name: Paperless-ngx
  page: /applications/document-management/paperless-ngx/
  slug: paperless-ngx
  url: https://github.com/paperless-ngx/paperless-ngx
- anchor: paperless-gpt
  counts:
    declared: 11
    observed: 3
  evidence:
  - route: dependency manifest
    url: https://github.com/icereed/paperless-gpt/blob/main/go.mod
  - route: documentation
    url: https://github.com/icereed/paperless-gpt
  integrations:
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Google Document AI
    provider: google-cloud-document-ai
    says: ships the Google Document AI SDK or integration code
    source: https://github.com/icereed/paperless-gpt/blob/main/go.mod
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
    name: Google Gemini
    provider: google-gemini
    says: ships the Google Gemini SDK or integration code
    source: https://github.com/icereed/paperless-gpt/blob/main/go.mod
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Ollama
    provider: ollama
    says: ships the Ollama SDK or integration code
    source: https://github.com/icereed/paperless-gpt/blob/main/go.mod
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
    says: lists Anthropic as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Azure Document Intelligence
    provider: microsoft-azure
    says: lists Azure Document Intelligence as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.20
      key: AE-110.10.20
      name: OpenAI-Compatible Endpoints
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Azure OpenAI
    provider: microsoft-azure-openai
    says: lists Azure OpenAI as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Docling Server
    provider: docling
    says: lists Docling Server as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.20
      key: AE-110.10.20
      name: OpenAI-Compatible Endpoints
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Groq
    provider: groq
    says: lists Groq as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.40
      key: AE-110.10.40
      name: On-Device & Edge Inference
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: LM Studio
    provider: lm-studio
    says: lists LM Studio as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    credit: null
    layer: domain
    name: Mistral AI
    provider: mistral
    says: lists Mistral AI as an integration
    source: https://github.com/icereed/paperless-gpt
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
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.30
      key: AE-110.10.30
      name: Model Routing & Gateways
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: OpenRouter
    provider: openrouter
    says: lists OpenRouter as an integration
    source: https://github.com/icereed/paperless-gpt
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
    name: Paperless-ngx
    provider: paperless-ngx
    says: lists Paperless-ngx as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.20
      key: AE-110.10.20
      name: OpenAI-Compatible Endpoints
      url: /capabilities/model-inference/
      via_parent: Model Inference
    credit: null
    layer: domain
    name: Together
    provider: together-ai
    says: lists Together as an integration
    source: https://github.com/icereed/paperless-gpt
    tier: declared
  kind: self-hosted
  name: paperless-gpt
  page: /applications/document-management/paperless-gpt/
  slug: paperless-gpt
  url: https://github.com/icereed/paperless-gpt
- anchor: stirling-pdf
  counts:
    declared: 0
    observed: 5
  evidence:
  - route: dependency manifest
    url: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/common/build.gradle
  - route: dependency manifest
    url: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/core/build.gradle
  - route: dependency manifest
    url: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/proprietary/build.gradle
  - route: dependency manifest
    url: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
  integrations:
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
    source: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
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
    source: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/common/build.gradle
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
    source: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
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
    name: Supabase
    provider: supabase
    says: ships the Supabase SDK or integration code
    source: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    credit: null
    layer: domain
    name: Telegram
    provider: telegram
    says: ships the Telegram SDK or integration code
    source: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/core/build.gradle
    tier: observed
  kind: open-source-saas
  name: Stirling-PDF
  page: /applications/document-management/stirling-pdf/
  slug: stirling-pdf
  url: https://github.com/Stirling-Tools/Stirling-PDF
- anchor: papra
  counts:
    declared: 0
    observed: 7
  evidence:
  - route: dependency manifest
    url: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
  integrations:
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
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
    tier: observed
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.50
      key: AE-150.10.50
      name: Inbound Email Processing
      url: /capabilities/email/
      via_parent: Email
    credit: null
    layer: domain
    name: OwlRelay
    provider: owlrelay
    says: ships the OwlRelay SDK or integration code
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    name: Resend
    provider: resend
    says: ships the Resend SDK or integration code
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
    source: https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
    tier: observed
  kind: open-source-saas
  name: Papra
  page: /applications/document-management/papra/
  slug: papra
  url: https://github.com/papra-hq/papra
- anchor: mayan-edms
  counts:
    declared: 0
    observed: 1
  evidence:
  - route: dependency manifest
    url: https://github.com/mayan-edms/Mayan-EDMS/blob/master/setup.py
  integrations:
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
    source: https://github.com/mayan-edms/Mayan-EDMS/blob/master/setup.py
    tier: observed
  kind: self-hosted
  name: Mayan EDMS
  page: /applications/document-management/mayan-edms/
  slug: mayan-edms
  url: https://github.com/mayan-edms/Mayan-EDMS
- anchor: docspell
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: dependency manifest
    url: https://github.com/eikek/docspell/blob/master/project/Dependencies.scala
  integrations: []
  kind: self-hosted
  name: Docspell
  page: /applications/document-management/docspell/
  slug: docspell
  url: https://github.com/eikek/docspell
- anchor: adobe-acrobat
  counts:
    declared: 25
    observed: 6
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
  - route: integrations page
    url: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Adobe Experience Cloud
    provider: adobe-experience-cloud
    says: ships the Adobe Experience Cloud SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
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
    name: Facebook Analytics
    provider: facebook
    says: ships the Facebook Analytics SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
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
    name: Facebook Login / Share
    provider: facebook
    says: ships the Facebook Login / Share SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
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
    name: Firebase (Crashlytics / Analytics)
    provider: firebase
    says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
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
    source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
    tier: observed
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: domain
    name: Agiloft
    provider: agiloft
    says: lists Agiloft as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Box
    provider: box
    says: lists Box as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
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
    says: lists Dropbox as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Egnyte Connect
    provider: egnyte
    says: lists Egnyte Connect as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
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
    says: lists Google Drive as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Hyland
    provider: hyland
    says: lists Hyland as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: domain
    name: Icertis
    provider: icertis
    says: lists Icertis as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    credit: null
    layer: domain
    name: Ironclad
    provider: ironclad
    says: lists Ironclad as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Laser Fiche
    provider: laserfiche
    says: lists Laser Fiche as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: M-Files
    provider: m-files
    says: lists M-Files as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft 365
    provider: microsoft-365
    says: lists Microsoft 365 as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Microsoft Dynamics 365
    provider: microsoft-dynamics-365
    says: lists Microsoft Dynamics 365 as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft OneDrive
    provider: microsoft-onedrive
    says: lists Microsoft OneDrive as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Microsoft SharePoint
    provider: sharepoint
    says: lists Microsoft SharePoint as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Nintex Workflow Cloud
    provider: nintex
    says: lists Nintex Workflow Cloud as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: ProcessMaker
    provider: processmaker
    says: lists ProcessMaker as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    credit: null
    layer: common
    name: SAP Ariba
    provider: ariba
    says: lists SAP Ariba as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    credit: null
    layer: common
    name: ServiceNow
    provider: servicenow
    says: lists ServiceNow as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: UiPath
    provider: uipath
    says: lists UiPath as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    credit: null
    layer: common
    name: Workday
    provider: workday
    says: lists Workday as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
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
    name: Xero
    provider: xero
    says: lists Xero as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Zoho Docs
    provider: zoho-workdrive
    says: lists Zoho Docs as an integration
    source: https://www.adobe.com/acrobat/business/integrations.html
    tier: declared
  kind: commercial
  name: Adobe Acrobat
  page: /applications/document-management/adobe-acrobat/
  slug: adobe-acrobat
  url: https://www.adobe.com/acrobat.html
author: API Evangelist
candidates: []
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
html: public
id: document-management
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Business
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Productivity
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Business
  store: google-play
  url: https://play.google.com/store/apps/category/BUSINESS
- category: Productivity
  store: google-play
  url: https://play.google.com/store/apps/category/PRODUCTIVITY
- category: Document Management
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#document-management
- category: Archiving and Digital Preservation (DP)
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#archiving-and-digital-preservation-dp
- category: Documentation
  store: atlassian-marketplace
  url: https://marketplace.atlassian.com/
- category: Documents
  store: zapier
  url: https://zapier.com/apps
name: Document Management & OCR
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.20
    key: AE-110.40.20
    name: OCR & Document AI
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  fit: exact
  layer: domain
  why: turning scans into searchable text is the category
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: auto-tagging, titling and Q&A over documents
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.40
    key: AE-110.10.40
    name: On-Device & Edge Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: self-hosted apps offer local models
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.10
    key: AE-110.60.10
    name: Embeddings
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  fit: exact
  layer: domain
  why: semantic search over the archive
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  fit: exact
  layer: domain
  why: mailbox ingestion of attachments
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.30
    key: AE-110.10.30
    name: Model Routing & Gateways
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: model routing gateways
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.20
    key: AE-110.10.20
    name: OpenAI-Compatible Endpoints
    url: /capabilities/model-inference/
    via_parent: Model Inference
  fit: exact
  layer: domain
  why: OpenAI-compatible endpoints as drop-in backends
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  fit: exact
  layer: domain
  why: enterprise content / DMS systems of record (nearest BC)
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  fit: exact
  layer: common
  why: product telemetry
- capability:
    attribution: Turbo EA
    id: BC-1340.20
    key: payment-processing-management
    name: Payment Processing Management
    url: /capabilities/payment-processing-management/
    via_parent: null
  fit: exact
  layer: common
  why: SaaS subscriptions
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: SaaS backend data
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  fit: exact
  layer: domain
  why: chat-bot document intake
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: documents live in user drives
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: common
  why: object storage for originals (nearest)
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.10
    key: AE-150.10.10
    name: Transactional Email
    url: /capabilities/email/
    via_parent: Email
  fit: exact
  layer: common
  why: notifications and invites
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: common
  why: error monitoring
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  fit: exact
  layer: domain
  why: document workflows hand off to automation
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  fit: exact
  layer: common
  why: send documents from CRM
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  fit: exact
  layer: common
  why: HR documents
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  fit: exact
  layer: common
  why: ITSM document flows
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  fit: exact
  layer: domain
  why: contract lifecycle
- capability:
    attribution: Turbo EA
    id: BC-500
    key: procurement-management
    name: Procurement Management
    url: /capabilities/procurement-management/
    via_parent: null
  fit: exact
  layer: common
  why: procurement documents
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
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  fit: exact
  layer: common
  why: accounting documents
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: social sign-in and share SDKs named in Exodus reports
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: install attribution and deep-link SDKs named in Exodus reports
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  fit: exact
  layer: common
  why: in-app advertising SDKs named in Exodus reports
stack:
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-916
      key: AE-916
      name: Cloud Drive & File Sync
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 44.4
      apps:
      - Adobe Acrobat
      - Stirling-PDF
      band: exemplar
      in_catalog: true
      kin_score: 73.2
      mcp:
        source: https://github.com/google/mcp
        status: verified
      name: Google Drive
      slug: google-drive
      sources:
      - https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Document Management
      - Drives
      tier: observed
      url: /providers/google-drive/
    - agent_band: agent-ready
      agent_readiness: 36.3
      apps:
      - Adobe Acrobat
      band: exemplar
      in_catalog: true
      kin_score: 76.1
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft 365
      slug: microsoft-365
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Calendar
      - Collaboration
      - Email
      - Productivity
      tier: declared
      url: /providers/microsoft-365/
    - agent_band: agent-ready
      agent_readiness: 56.6
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 63.0
      mcp:
        source: https://developer.box.com/guides/box-mcp/
        status: verified
      name: Box
      slug: box
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Content Management
      - Documents
      tier: declared
      url: /providers/box/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 50.9
      mcp:
        status: none
      name: Microsoft OneDrive
      slug: microsoft-onedrive
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - File
      - File Storage
      - Microsoft
      tier: declared
      url: /providers/microsoft-onedrive/
    - agent_band: agent-ready
      agent_readiness: 44.8
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 45.9
      mcp:
        source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
        status: verified
      name: Dropbox
      slug: dropbox
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - Documents
      - Storage
      tier: declared
      url: /providers/dropbox/
    - agent_band: agent-aware
      agent_readiness: 26.4
      apps:
      - Adobe Acrobat
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/egnyte/egnyte-mcp-server
        status: verified
      name: Egnyte Connect
      slug: egnyte
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Content Collaboration
      - Document Management
      - Enterprise Storage
      - File Sharing
      tier: declared
      url: /providers/egnyte/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Adobe Acrobat
      band: emerging
      in_catalog: true
      kin_score: 23.7
      mcp:
        source: https://www.zoho.com/workdrive/mcp.html
        status: verified
      name: Zoho Docs
      slug: zoho-workdrive
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Cloud Storage
      - Collaboration
      - File Management
      - Zoho
      tier: declared
      url: /providers/zoho-workdrive/
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
      - Paperless-ngx
      - Papra
      - paperless-gpt
      band: exemplar
      in_catalog: true
      kin_score: 82.5
      mcp:
        source: https://platform.openai.com/docs/mcp
        status: verified
      name: OpenAI
      slug: openai
      sources:
      - https://github.com/icereed/paperless-gpt
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
      status: profiled
      tags:
      - Artificial Intelligence
      - Generative AI
      - LLM
      - OpenAI
      tier: observed
      url: /providers/openai/
    - agent_band: agent-ready
      agent_readiness: 46.6
      apps:
      - Papra
      - paperless-gpt
      band: exemplar
      in_catalog: true
      kin_score: 86.4
      mcp:
        source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
        status: verified
      name: Anthropic
      slug: anthropic
      sources:
      - https://github.com/icereed/paperless-gpt
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
      status: profiled
      tags:
      - Anthropic
      - Artificial Intelligence
      - Claude
      - LLM
      tier: observed
      url: /providers/anthropic/
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - paperless-gpt
      band: strong
      in_catalog: true
      kin_score: 61.7
      mcp:
        status: none
      name: Google Gemini
      slug: google-gemini
      sources:
      - https://github.com/icereed/paperless-gpt/blob/main/go.mod
      status: profiled
      tags:
      - AI Agents
      - Artificial Intelligence
      - Code Generation
      - Embeddings
      tier: observed
      url: /providers/google-gemini/
  - capability:
      attribution: API Evangelist extension
      id: AE-917
      key: AE-917
      name: Enterprise Content & Document Management
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 32.3
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 60.9
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Microsoft SharePoint
      slug: sharepoint
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Collaboration
      - Document Management
      - Enterprise Content Management
      - Intranet
      tier: declared
      url: /providers/sharepoint/
    - agent_band: agent-aware
      agent_readiness: 14.8
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 48.3
      mcp:
        status: none
      name: Laser Fiche
      slug: laserfiche
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Company
      - Document Management
      - Enterprise Content Management
      - Process Automation
      tier: declared
      url: /providers/laserfiche/
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - Adobe Acrobat
      band: thin
      in_catalog: true
      kin_score: 35.6
      mcp:
        status: none
      name: M-Files
      slug: m-files
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Company
      - Document Management
      - Information Management
      - Infrastructure Saas
      tier: declared
      url: /providers/m-files/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - paperless-gpt
      band: minimal
      in_catalog: true
      kin_score: 0.4
      mcp:
        status: none
      name: Paperless-ngx
      slug: paperless-ngx
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Company
      tier: declared
      url: /providers/paperless-ngx/
    - agent_band: null
      agent_readiness: null
      apps:
      - Adobe Acrobat
      band: null
      in_catalog: false
      kin_score: null
      mcp:
        status: unchecked
      name: Hyland
      slug: hyland
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: queued for profiling
      tags: []
      tier: declared
      url: null
  - capability:
      attribution: API Evangelist extension
      id: AE-110.40.20
      key: AE-110.40.20
      name: OCR & Document AI
      url: /capabilities/language-document-understanding/
      via_parent: Language & Document Understanding
    providers:
    - agent_band: agent-ready
      agent_readiness: 45.0
      apps:
      - Paperless-ngx
      - paperless-gpt
      band: exemplar
      in_catalog: true
      kin_score: 76.0
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure AI Document Intelligence
      slug: microsoft-azure
      sources:
      - https://github.com/icereed/paperless-gpt
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
      status: profiled
      tags:
      - Cloud
      - Cloud Computing
      - Enterprise
      - Microsoft Azure
      tier: observed
      url: /providers/microsoft-azure/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - paperless-gpt
      band: strong
      in_catalog: true
      kin_score: 64.3
      mcp:
        status: none
      name: Google Document AI
      slug: google-cloud-document-ai
      sources:
      - https://github.com/icereed/paperless-gpt/blob/main/go.mod
      status: profiled
      tags:
      - Data Extraction
      - Document Processing
      - Forms
      - Google Cloud
      tier: observed
      url: /providers/google-cloud-document-ai/
    - agent_band: agent-aware
      agent_readiness: 28.2
      apps:
      - paperless-gpt
      band: developing
      in_catalog: true
      kin_score: 47.3
      mcp:
        status: none
      name: Mistral AI
      slug: mistral
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Agents
      - Embeddings
      - Machine Learning
      - OCR
      tier: declared
      url: /providers/mistral/
    - agent_band: agent-aware
      agent_readiness: 24.1
      apps:
      - paperless-gpt
      band: thin
      in_catalog: true
      kin_score: 37.9
      mcp:
        source: https://github.com/docling-project/docling-mcp
        status: verified
      name: Docling Server
      slug: docling
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Documents
      - OCR
      - PDF
      - Parsing
      tier: declared
      url: /providers/docling/
  - capability:
      attribution: Turbo EA
      id: BC-150.10
      key: contract-management
      name: Contract Management
      url: /capabilities/contract-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.0
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 52.3
      mcp:
        status: none
      name: Ironclad
      slug: ironclad
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Contract Lifecycle Management
      - Contracts
      - Legal Tech
      - LegalOps
      tier: declared
      url: /providers/ironclad/
    - agent_band: agent-ready
      agent_readiness: 31.5
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 52.1
      mcp:
        status: none
      name: Agiloft
      slug: agiloft
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Contract Lifecycle Management
      - Contract Management
      - Legal
      - Procurement
      tier: declared
      url: /providers/agiloft/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Adobe Acrobat
      band: emerging
      in_catalog: true
      kin_score: 12.9
      mcp:
        status: none
      name: Icertis
      slug: icertis
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Company
      - Contract Intelligence
      - Contract Lifecycle Management
      - Enterprise
      tier: declared
      url: /providers/icertis/
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
      - Paperless-ngx
      - paperless-gpt
      band: thin
      in_catalog: true
      kin_score: 37.7
      mcp:
        status: none
      name: Ollama
      slug: ollama
      sources:
      - https://github.com/icereed/paperless-gpt/blob/main/go.mod
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
      status: profiled
      tags:
      - Artificial Intelligence
      - LLM
      - Models
      - Ollama
      tier: observed
      url: /providers/ollama/
    - agent_band: agent-aware
      agent_readiness: 22.5
      apps:
      - paperless-gpt
      band: thin
      in_catalog: true
      kin_score: 32.2
      mcp:
        status: none
      name: LM Studio
      slug: lm-studio
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Artificial Intelligence
      - Company
      - Local LLM
      - Machine Learning
      tier: declared
      url: /providers/lm-studio/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.10.20
      key: AE-110.10.20
      name: OpenAI-Compatible Endpoints
      url: /capabilities/model-inference/
      via_parent: Model Inference
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.9
      apps:
      - paperless-gpt
      band: exemplar
      in_catalog: true
      kin_score: 68.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure OpenAI
      slug: microsoft-azure-openai
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Artificial Intelligence
      - Embeddings
      - GPT
      - Generative AI
      tier: declared
      url: /providers/microsoft-azure-openai/
    - agent_band: agent-ready
      agent_readiness: 40.0
      apps:
      - paperless-gpt
      band: thin
      in_catalog: true
      kin_score: 34.4
      mcp:
        source: https://docs.together.ai/docs/mcp
        status: verified
      name: Together
      slug: together-ai
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Artificial Intelligence
      - Foundation Models
      - Inference
      - LLM
      tier: declared
      url: /providers/together-ai/
    - agent_band: agent-aware
      agent_readiness: 21.2
      apps:
      - paperless-gpt
      band: thin
      in_catalog: true
      kin_score: 32.3
      mcp:
        source: https://github.com/groq/groq-mcp-server
        status: verified
      name: Groq
      slug: groq
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Artificial Intelligence
      - Inference
      - LLM
      - LPU
      tier: declared
      url: /providers/groq/
  - capability:
      attribution: API Evangelist extension
      id: AE-918
      key: AE-918
      name: Document Generation & Conversion
      url: /capabilities/it-application-management/
      via_parent: IT Application Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 16.8
      apps:
      - Paperless-ngx
      band: thin
      in_catalog: true
      kin_score: 33.1
      mcp:
        status: none
      name: Apache Tika
      slug: apache-tika
      sources:
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
      status: profiled
      tags:
      - Content Extraction
      - Document Processing
      - Metadata
      - Text Extraction
      tier: observed
      url: /providers/apache-tika/
    - agent_band: agent-aware
      agent_readiness: 18.6
      apps:
      - Paperless-ngx
      band: emerging
      in_catalog: true
      kin_score: 23.4
      mcp:
        status: none
      name: Gotenberg
      slug: gotenberg
      sources:
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
      status: profiled
      tags:
      - Conversion
      - Docker
      - Open Source
      - PDF
      tier: observed
      url: /providers/gotenberg/
  - capability:
      attribution: API Evangelist extension
      id: AE-110.60.10
      key: AE-110.60.10
      name: Embeddings
      url: /capabilities/retrieval-embeddings/
      via_parent: Retrieval & Embeddings
    providers:
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Paperless-ngx
      band: exemplar
      in_catalog: true
      kin_score: 69.1
      mcp:
        source: https://github.com/huggingface/hf-mcp-server
        status: verified
      name: Hugging Face
      slug: hugging-face
      sources:
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/pyproject.toml
      status: profiled
      tags:
      - Computer Vision
      - Embeddings
      - Image Generation
      - LLM
      tier: observed
      url: /providers/hugging-face/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.50
      key: AE-150.10.50
      name: Inbound Email Processing
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Papra
      band: emerging
      in_catalog: true
      kin_score: 20.0
      mcp:
        status: none
      name: OwlRelay
      slug: owlrelay
      sources:
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
      status: profiled
      tags:
      - Company
      - Email
      - Open Source
      - Webhook
      tier: observed
      url: /providers/owlrelay/
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
      - paperless-gpt
      band: strong
      in_catalog: true
      kin_score: 54.8
      mcp:
        source: https://openrouter.ai/docs/guides/overview/mcp-server
        status: verified
      name: OpenRouter
      slug: openrouter
      sources:
      - https://github.com/icereed/paperless-gpt
      status: profiled
      tags:
      - Artificial Intelligence
      - Gateways
      - LLM
      - Router
      tier: declared
      url: /providers/openrouter/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.20.20
      key: AE-150.20.20
      name: WhatsApp & OTT Messaging
      url: /capabilities/sms-messaging-apps/
      via_parent: SMS & Messaging Apps
    providers:
    - agent_band: agent-aware
      agent_readiness: 25.3
      apps:
      - Stirling-PDF
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        status: none
      name: Telegram
      slug: telegram
      sources:
      - https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/core/build.gradle
      status: profiled
      tags:
      - Bots
      - Chat
      - Messaging
      - Notification
      tier: observed
      url: /providers/telegram/
  layer: domain
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4280.30
      key: product-usage-analytics
      name: Product Usage Analytics
      url: /capabilities/product-usage-analytics/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 56.2
      apps:
      - Papra
      - Stirling-PDF
      band: strong
      in_catalog: true
      kin_score: 57.9
      mcp:
        source: https://github.com/PostHog/mcp
        status: verified
      name: PostHog
      slug: posthog
      sources:
      - https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/common/build.gradle
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
      status: profiled
      tags:
      - A/B Testing
      - Analytics
      - Feature Flags
      - Open Source
      tier: observed
      url: /providers/posthog/
    - agent_band: agent-ready
      agent_readiness: 53.0
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 65.1
      mcp:
        source: https://github.com/adobe/cq-quickstart-mcp-server
        status: verified
      name: Adobe Experience Cloud
      slug: adobe-experience-cloud
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
      status: profiled
      tags:
      - Analytics
      - Customer Experience
      - Digital Marketing
      - Personalization
      tier: observed
      url: /providers/adobe-experience-cloud/
    - agent_band: agent-ready
      agent_readiness: 39.9
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 62.0
      mcp:
        source: https://firebase.google.com/docs/ai-assistance/mcp-server
        status: verified
      name: Firebase (Crashlytics / Analytics)
      slug: google-firebase
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
      status: profiled
      tags:
      - Analytics
      - Authentication
      - Backend-as-a-Service
      - Cloud Messaging
      tier: observed
      url: /providers/google-firebase/
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: &id001
        status: none
      name: Facebook Analytics
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
      status: profiled
      tags: &id002
      - Advertising
      - Content Publishing
      - Facebook
      - Fortune 500
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: API Evangelist extension
      id: AE-910
      key: AE-910
      name: Workflow Automation & iPaaS
      url: /capabilities/process-automation-governance/
      via_parent: Process Automation Governance
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.5
      apps:
      - Adobe Acrobat
      band: exemplar
      in_catalog: true
      kin_score: 71.0
      mcp:
        source: https://github.com/UiPath/uipath-mcp-python
        status: verified
      name: UiPath
      slug: uipath
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Artificial Intelligence
      - Automation
      - Document Processing
      - RPA
      tier: declared
      url: /providers/uipath/
    - agent_band: agent-ready
      agent_readiness: 43.0
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 43.4
      mcp:
        source: https://github.com/integromat/make-mcp-server
        status: verified
      name: Make
      slug: make
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Automation
      - Integration
      - No-Code
      - iPaaS
      tier: declared
      url: /providers/make/
    - agent_band: agent-ready
      agent_readiness: 29.5
      apps:
      - Adobe Acrobat
      band: thin
      in_catalog: true
      kin_score: 28.9
      mcp:
        status: none
      name: ProcessMaker
      slug: processmaker
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - BPMN 2.0
      - Business Process Management
      - Low-Code
      - Workflow Automation
      tier: declared
      url: /providers/processmaker/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Adobe Acrobat
      band: emerging
      in_catalog: true
      kin_score: 19.9
      mcp:
        status: none
      name: Nintex Workflow Cloud
      slug: nintex
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Automation
      - Company
      - Low-Code
      - Workflows
      tier: declared
      url: /providers/nintex/
  - capability:
      attribution: Turbo EA
      id: BC-420
      key: customer-relationship-management
      name: Customer Relationship Management
      url: /capabilities/customer-relationship-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 53.6
      apps:
      - Adobe Acrobat
      band: exemplar
      in_catalog: true
      kin_score: 88.0
      mcp:
        source: https://github.com/salesforcecli/mcp
        status: verified
      name: Salesforce
      slug: salesforce
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Analytics
      - Artificial Intelligence
      - Cloud
      - Fortune 500
      tier: declared
      url: /providers/salesforce/
    - agent_band: agent-ready
      agent_readiness: 37.6
      apps:
      - Adobe Acrobat
      band: exemplar
      in_catalog: true
      kin_score: 67.7
      mcp:
        source: https://github.com/microsoft/Dataverse-MCP
        status: verified
      name: Microsoft Dynamics 365
      slug: microsoft-dynamics-365
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Business Applications
      - CRM
      - Cloud
      - Enterprise
      tier: declared
      url: /providers/microsoft-dynamics-365/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.80
      key: AE-150.80
      name: Mailbox & Calendar Sync
      url: /capabilities/mailbox-calendar-sync/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.9
      apps:
      - Paperless-ngx
      band: exemplar
      in_catalog: true
      kin_score: 70.8
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Outlook
      slug: microsoft-outlook
      sources:
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/docs/configuration.md
      status: profiled
      tags:
      - Calendar
      - Contacts
      - Email
      - Enterprise
      tier: declared
      url: /providers/microsoft-outlook/
    - agent_band: agent-ready
      agent_readiness: 43.2
      apps:
      - Paperless-ngx
      band: exemplar
      in_catalog: true
      kin_score: 66.8
      mcp:
        source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
        status: verified
      name: Gmail
      slug: google-gmail
      sources:
      - https://github.com/paperless-ngx/paperless-ngx/blob/dev/docs/configuration.md
      status: profiled
      tags:
      - Drafts
      - Email
      - Gmail
      - Google
      tier: declared
      url: /providers/google-gmail/
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
      - Papra
      - Stirling-PDF
      band: exemplar
      in_catalog: true
      kin_score: 82.0
      mcp:
        source: https://docs.stripe.com/mcp
        status: verified
      name: Stripe
      slug: stripe
      sources:
      - https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
      status: profiled
      tags:
      - Commerce
      - Financial Services
      - Fintech
      - Payments
      tier: observed
      url: /providers/stripe/
  - capability:
      attribution: Turbo EA
      id: BC-200.10
      key: general-ledger-management
      name: General Ledger Management
      url: /capabilities/general-ledger-management/
      via_parent: null
    providers:
    - agent_band: agent-native
      agent_readiness: 60.0
      apps:
      - Adobe Acrobat
      band: exemplar
      in_catalog: true
      kin_score: 87.1
      mcp:
        source: https://github.com/XeroAPI/xero-mcp-server
        status: verified
      name: Xero
      slug: xero
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Accounting
      - Bank Feeds
      - Finance
      - Financial Services
      tier: declared
      url: /providers/xero/
  - capability:
      attribution: Turbo EA
      id: BC-300
      key: human-capital-management
      name: Human Capital Management
      url: /capabilities/human-capital-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.3
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 54.7
      mcp:
        status: none
      name: Workday
      slug: workday
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Cloud Computing
      - Enterprise Software
      - Financial Management
      - HCM
      tier: declared
      url: /providers/workday/
  - capability:
      attribution: Turbo EA
      id: BC-600.30
      key: it-service-management
      name: IT Service Management
      url: /capabilities/it-service-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 42.3
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 61.9
      mcp:
        status: none
      name: ServiceNow
      slug: servicenow
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Automation
      - Cloud Services
      - Digital Workflows
      - ServiceNow
      tier: declared
      url: /providers/servicenow/
  - capability:
      attribution: API Evangelist extension
      id: AE-903
      key: AE-903
      name: In-App Ad Monetisation
      url: /capabilities/in-app-ad-monetisation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - Adobe Acrobat
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        status: none
      name: Google AdMob
      slug: google-admob
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
      status: profiled
      tags:
      - Ad Mediation
      - AdMob
      - Advertising
      - App Monetization
      tier: observed
      url: /providers/google-admob/
  - capability:
      attribution: API Evangelist extension
      id: AE-915
      key: AE-915
      name: Managed Operational Databases
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.2
      apps:
      - Stirling-PDF
      band: developing
      in_catalog: true
      kin_score: 49.4
      mcp:
        source: https://github.com/supabase/mcp
        status: verified
      name: Supabase
      slug: supabase
      sources:
      - https://github.com/Stirling-Tools/Stirling-PDF/blob/main/frontend/package.json
      status: profiled
      tags:
      - Authentication
      - Backend-as-a-Service
      - Open Source
      - PostgreSQL
      tier: observed
      url: /providers/supabase/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.9
      apps:
      - Adobe Acrobat
      band: thin
      in_catalog: true
      kin_score: 33.8
      mcp:
        status: none
      name: Branch
      slug: branch-io
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
      status: profiled
      tags:
      - Company
      tier: observed
      url: /providers/branch-io/
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
      - Mayan EDMS
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://github.com/mayan-edms/Mayan-EDMS/blob/master/setup.py
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  - capability:
      attribution: Turbo EA
      id: BC-500
      key: procurement-management
      name: Procurement Management
      url: /capabilities/procurement-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.0
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 45.7
      mcp:
        status: none
      name: SAP Ariba
      slug: ariba
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - B2B
      - Catalog Management
      - Compliance
      - Contracts
      tier: declared
      url: /providers/ariba/
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-aware
      agent_readiness: 28.1
      apps:
      - Adobe Acrobat
      band: developing
      in_catalog: true
      kin_score: 43.7
      mcp: *id001
      name: Facebook Login / Share
      slug: facebook
      sources:
      - https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/facebook/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Papra
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
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
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Adobe Acrobat
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://www.adobe.com/acrobat/business/integrations.html
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
  - capability:
      attribution: API Evangelist extension
      id: AE-150.10.10
      key: AE-150.10.10
      name: Transactional Email
      url: /capabilities/email/
      via_parent: Email
    providers:
    - agent_band: agent-ready
      agent_readiness: 49.8
      apps:
      - Papra
      band: strong
      in_catalog: true
      kin_score: 56.8
      mcp:
        source: https://resend.com/docs/mcp-server
        status: verified
      name: Resend
      slug: resend
      sources:
      - https://github.com/papra-hq/papra/blob/main/apps/papra-server/package.json
      status: profiled
      tags:
      - Developer Tools
      - Email
      - Marketing Email
      - Transactional Email
      tier: observed
      url: /providers/resend/
  layer: common
summary:
  coverage_pct: 98.2
  declared_only: 34
  distinct_providers: 57
  in_catalog: 56
  mcp:
    documented: 0
    none: 24
    unchecked: 1
    verified: 32
  mcp_verified: 32
  mean_kin_score: 53.5
  observed: 23
  queued: 1
  reference_apps: 7
title: 'Document Management & OCR: application blueprint'
---
