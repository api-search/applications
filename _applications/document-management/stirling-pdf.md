---
app: Stirling-PDF
app_slug: stirling-pdf
app_url: https://github.com/Stirling-Tools/Stirling-PDF
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Google Drive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
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
category:
  id: document-management
  name: Document Management & OCR
  url: /applications/document-management/
counts:
  declared: 0
  observed: 5
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id001
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id002
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 56.2
    band: strong
    in_catalog: true
    kin_score: 57.9
    mcp: &id003
      source: https://github.com/PostHog/mcp
      status: verified
    slug: posthog
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Feature Flags
    - Open Source
    url: /providers/posthog/
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
  facts:
    agent_band: agent-native
    agent_readiness: 57.6
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id005
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id006
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id007
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id008
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id009
      status: none
    slug: telegram
    status: profiled
    tags: &id010
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram
  provider: telegram
  says: ships the Telegram SDK or integration code
  source: https://github.com/Stirling-Tools/Stirling-PDF/blob/main/app/core/build.gradle
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/document-management/stirling-pdf/
providers:
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id001
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id002
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 56.2
  band: strong
  in_catalog: true
  kin_score: 57.9
  mcp: *id003
  name: PostHog
  slug: posthog
  status: profiled
  tags: *id004
  url: /providers/posthog/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id005
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id006
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id007
  name: Supabase
  slug: supabase
  status: profiled
  tags: *id008
  url: /providers/supabase/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id009
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id010
  url: /providers/telegram/
siblings:
- name: Adobe Acrobat
  rows: 31
  url: /applications/document-management/adobe-acrobat/
- name: Docspell
  rows: 0
  url: /applications/document-management/docspell/
- name: Mayan EDMS
  rows: 1
  url: /applications/document-management/mayan-edms/
- name: paperless-gpt
  rows: 14
  url: /applications/document-management/paperless-gpt/
- name: Paperless-ngx
  rows: 8
  url: /applications/document-management/paperless-ngx/
- name: Papra
  rows: 7
  url: /applications/document-management/papra/
sitemap: true
title: 'Stirling-PDF: Document Management & OCR reference app'
---
