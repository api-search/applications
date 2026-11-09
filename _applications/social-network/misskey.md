---
app: Misskey
app_slug: misskey
app_url: https://github.com/misskey-dev/misskey
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: domain
  name: Machine Translation
  providers:
  - DeepL
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  - Google reCAPTCHA
  - hCaptcha
  - mCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - PostgreSQL
  - Redis
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
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-830.20.30
  key: BC-830.20.30
  layer: common
  name: Search and Discovery Management
  providers:
  - Meilisearch
  url: /capabilities/knowledge-curation-taxonomy-management/
  via_parent: Knowledge Curation & Taxonomy Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: social-network
  name: Social Networking & Microblogging
  url: /applications/social-network/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
- route: dependency manifest
  url: https://github.com/misskey-dev/misskey/blob/develop/packages/frontend/package.json
- route: source code
  url: https://github.com/misskey-dev/misskey/blob/develop/.config/example.yml
- route: source code
  url: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
- route: source code
  url: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/server/api/endpoints/notes/translate.ts
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
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
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id003
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id004
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
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
    agent_readiness: 36.4
    band: strong
    in_catalog: true
    kin_score: 60.8
    mcp: &id005
      source: https://github.com/DeepL/deepl-mcp-server
      status: verified
    slug: deepl
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Deep Learning
    - Glossary
    - Localization
    url: /providers/deepl/
  layer: domain
  name: DeepL
  provider: deepl
  says: ships the DeepL SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/server/api/endpoints/notes/translate.ts
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
    agent_readiness: 41.8
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id007
      source: https://developers.google.com/analytics/devguides/MCP
      status: verified
    slug: google-analytics
    status: profiled
    tags: &id008
    - Analytics
    - Data
    - Google
    - Metrics
    url: /providers/google-analytics/
  layer: common
  name: Google Analytics
  provider: google-analytics
  says: ships the Google Analytics SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/frontend/package.json
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
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id009
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id010
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id011
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id012
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
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
    agent_readiness: 15.8
    band: emerging
    in_catalog: true
    kin_score: 23.0
    mcp: &id013
      status: none
    slug: mcaptcha
    status: profiled
    tags: &id014
    - CAPTCHA
    - Company
    - Open Source
    - Privacy
    url: /providers/mcaptcha/
  layer: common
  name: mCaptcha
  provider: mcaptcha
  says: ships the mCaptcha SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/src/core/CaptchaService.ts
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-830.20.30
    key: BC-830.20.30
    name: Search and Discovery Management
    url: /capabilities/knowledge-curation-taxonomy-management/
    via_parent: Knowledge Curation & Taxonomy Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: developing
    in_catalog: true
    kin_score: 52.0
    mcp: &id015
      source: https://github.com/meilisearch/meilisearch-mcp
      status: verified
    slug: meilisearch
    status: profiled
    tags: &id016
    - AI Search
    - Full-Text Search
    - Hybrid Search
    - Open Source
    url: /providers/meilisearch/
  layer: common
  name: Meilisearch
  provider: meilisearch
  says: ships the Meilisearch SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/.config/example.yml
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.2
    mcp: &id017
      status: none
    slug: postgresql
    status: profiled
    tags: &id018
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: common
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
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
    agent_band: agent-native
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id019
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id020
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
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
    kin_score: 80.6
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
  source: https://github.com/misskey-dev/misskey/blob/develop/packages/backend/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-network/misskey/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id003
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id004
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 36.4
  band: strong
  in_catalog: true
  kin_score: 60.8
  mcp: *id005
  name: DeepL
  slug: deepl
  status: profiled
  tags: *id006
  url: /providers/deepl/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id007
  name: Google Analytics
  slug: google-analytics
  status: profiled
  tags: *id008
  url: /providers/google-analytics/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id009
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id010
  url: /providers/google-recaptcha/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id011
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id012
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 15.8
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id013
  name: mCaptcha
  slug: mcaptcha
  status: profiled
  tags: *id014
  url: /providers/mcaptcha/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: developing
  in_catalog: true
  kin_score: 52.0
  mcp: *id015
  name: Meilisearch
  slug: meilisearch
  status: profiled
  tags: *id016
  url: /providers/meilisearch/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id017
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id018
  url: /providers/postgresql/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id019
  name: Redis
  slug: redis
  status: profiled
  tags: *id020
  url: /providers/redis/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id021
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id022
  url: /providers/sentry-system/
siblings:
- name: Bluesky
  rows: 4
  url: /applications/social-network/bluesky/
- name: Friendica
  rows: 20
  url: /applications/social-network/friendica/
- name: Instagram
  rows: 2
  url: /applications/social-network/instagram/
- name: Mastodon
  rows: 9
  url: /applications/social-network/mastodon/
- name: Pixelfed
  rows: 11
  url: /applications/social-network/pixelfed/
- name: Threads
  rows: 2
  url: /applications/social-network/threads/
sitemap: true
title: 'Misskey: Social Networking & Microblogging reference app'
---
