---
app: Readest
app_slug: readest
app_url: https://github.com/readest/readest
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - Azure Translator
  - DeepL
  - Google Translate
  - Yandex Translate
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Apple (iCloud)
  - Google Drive
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-932
  key: AE-932
  layer: common
  name: Edge Functions & Edge Config Stores
  providers:
  - Cloudflare
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Google Play
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Supabase
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
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
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - Stripe
  url: /capabilities/payment-processing-management/
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
  id: ebooks-reading
  name: E-books, Reading & Comics
  url: /applications/ebooks-reading/
counts:
  declared: 0
  observed: 14
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
- route: source code
  url: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers
- route: source code
  url: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers
integrations:
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
    agent_readiness: 36.5
    band: developing
    in_catalog: true
    kin_score: 52.9
    mcp: &id001
      status: none
    slug: apple
    status: profiled
    tags: &id002
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
  layer: common
  name: Apple (iCloud)
  provider: apple
  says: ships the Apple (iCloud) SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/icloud
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
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id004
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: domain
  name: Azure Translator
  provider: microsoft-azure
  says: ships the Azure Translator SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/azure.ts
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-932
    key: AE-932
    name: Edge Functions & Edge Config Stores
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id005
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id006
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare
  provider: cloudflare
  says: ships the Cloudflare SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    mcp: &id007
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/deepl.ts
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
    mcp: &id009
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: ships the Google Drive SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/gdrive
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.7
    band: developing
    in_catalog: true
    kin_score: 51.3
    mcp: &id011
      status: none
    slug: google-play
    status: profiled
    tags: &id012
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play
  provider: google-play
  says: ships the Google Play SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    mcp: &id013
      status: none
    slug: google-translate
    status: profiled
    tags: &id014
    - Google Cloud
    - Internationalization
    - Language Detection
    - Localization
    url: /providers/google-translate/
  layer: domain
  name: Google Translate
  provider: google-translate
  says: ships the Google Translate SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/google.ts
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
    mcp: &id015
      status: none
    slug: ollama
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    mcp: &id017
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id018
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: ships the OneDrive SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/sync/providers/onedrive
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
    mcp: &id019
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id020
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
  layer: common
  name: PostHog
  provider: posthog
  says: ships the PostHog SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    mcp: &id021
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id022
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id023
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id024
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id025
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id026
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
  layer: common
  name: Supabase
  provider: supabase
  says: ships the Supabase SDK or integration code
  source: https://github.com/readest/readest/blob/main/apps/readest-app/package.json
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
    agent_readiness: 29.9
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id027
      status: none
    slug: yandex-translate
    status: profiled
    tags: &id028
    - Language Detection
    - Machine Translation
    - Natural Language Processing
    - Translation Dictionary
    url: /providers/yandex-translate/
  layer: domain
  name: Yandex Translate
  provider: yandex-translate
  says: ships the Yandex Translate SDK or integration code
  source: https://github.com/readest/readest/tree/main/apps/readest-app/src/services/translators/providers/yandex.ts
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ebooks-reading/readest/
providers:
- agent_band: agent-ready
  agent_readiness: 36.5
  band: developing
  in_catalog: true
  kin_score: 52.9
  mcp: *id001
  name: Apple (iCloud)
  slug: apple
  status: profiled
  tags: *id002
  url: /providers/apple/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id003
  name: Azure Translator
  slug: microsoft-azure
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure/
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id005
  name: Cloudflare
  slug: cloudflare
  status: profiled
  tags: *id006
  url: /providers/cloudflare/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id007
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id008
  url: /providers/deepl/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id009
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id010
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: developing
  in_catalog: true
  kin_score: 51.3
  mcp: *id011
  name: Google Play
  slug: google-play
  status: profiled
  tags: *id012
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 33.9
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id013
  name: Google Translate
  slug: google-translate
  status: profiled
  tags: *id014
  url: /providers/google-translate/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id015
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id016
  url: /providers/ollama/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id017
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id018
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id019
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id020
  url: /providers/posthog/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id021
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id022
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id023
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id024
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id025
  name: Supabase
  slug: supabase
  status: profiled
  tags: *id026
  url: /providers/supabase/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id027
  name: Yandex Translate
  slug: yandex-translate
  status: profiled
  tags: *id028
  url: /providers/yandex-translate/
siblings:
- name: Calibre-Web
  rows: 11
  url: /applications/ebooks-reading/calibre-web/
- name: Goodreads
  rows: 3
  url: /applications/ebooks-reading/goodreads/
- name: Kavita
  rows: 3
  url: /applications/ebooks-reading/kavita/
- name: Kindle
  rows: 2
  url: /applications/ebooks-reading/kindle/
- name: Komga
  rows: 1
  url: /applications/ebooks-reading/komga/
- name: KOReader
  rows: 3
  url: /applications/ebooks-reading/koreader/
sitemap: true
title: 'Readest: E-books, Reading & Comics reference app'
---
