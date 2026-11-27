---
app: Payload
app_slug: payload
app_url: https://github.com/payloadcms/payload
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Cloudflare D1
  - Vercel Postgres / Blob
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
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Cloudflare R2
  - Google Cloud Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Resend
  url: /capabilities/email/
  via_parent: Email
category:
  id: website-builder-cms
  name: Website Builder, CMS & Blogging
  url: /applications/website-builder-cms/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: source code
  url: https://github.com/payloadcms/payload/tree/main/packages
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
  source: https://github.com/payloadcms/payload/tree/main/packages/storage-s3
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
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id004
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/storage-azure
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
    agent_readiness: 30.3
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id005
      source: https://github.com/cloudflare/mcp-server-cloudflare
      status: verified
    slug: cloudflare-d1
    status: profiled
    tags: &id006
    - Database
    - Edge Computing
    - SQLite
    - Serverless
    url: /providers/cloudflare-d1/
  layer: common
  name: Cloudflare D1
  provider: cloudflare-d1
  says: ships the Cloudflare D1 SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/db-d1-sqlite
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
    agent_readiness: 28.7
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id007
      source: https://raw.githubusercontent.com/cloudflare/mcp/main/README.md
      status: verified
    slug: cloudflare-r2
    status: profiled
    tags: &id008
    - Cloud Storage
    - Egress-Free
    - Object Storage
    - S3 Compatible
    url: /providers/cloudflare-r2/
  layer: common
  name: Cloudflare R2
  provider: cloudflare-r2
  says: ships the Cloudflare R2 SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/storage-r2
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
    agent_readiness: 45.1
    band: exemplar
    in_catalog: true
    kin_score: 74.1
    mcp: &id009
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id010
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/storage-gcs
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
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id011
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id012
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/email-resend
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
    mcp: &id013
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id014
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/plugin-sentry
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
    mcp: &id015
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id016
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: common
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/plugin-stripe
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
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id017
      source: https://vercel.com/docs/mcp/vercel-mcp
      status: verified
    slug: vercel
    status: profiled
    tags: &id018
    - AI Gateway
    - Gateways
    - Observability
    - Webhook
    url: /providers/vercel/
  layer: common
  name: Vercel Postgres / Blob
  provider: vercel
  says: ships the Vercel Postgres / Blob SDK or integration code
  source: https://github.com/payloadcms/payload/tree/main/packages/db-vercel-postgres
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/website-builder-cms/payload/
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
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id003
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id005
  name: Cloudflare D1
  slug: cloudflare-d1
  status: profiled
  tags: *id006
  url: /providers/cloudflare-d1/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id007
  name: Cloudflare R2
  slug: cloudflare-r2
  status: profiled
  tags: *id008
  url: /providers/cloudflare-r2/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id009
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id010
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id011
  name: Resend
  slug: resend
  status: profiled
  tags: *id012
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id013
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id014
  url: /providers/sentry-system/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id015
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id016
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id017
  name: Vercel Postgres / Blob
  slug: vercel
  status: profiled
  tags: *id018
  url: /providers/vercel/
siblings:
- name: Directus
  rows: 12
  url: /applications/website-builder-cms/directus/
- name: Ghost
  rows: 76
  url: /applications/website-builder-cms/ghost/
- name: Strapi
  rows: 5
  url: /applications/website-builder-cms/strapi/
- name: Webflow
  rows: 17
  url: /applications/website-builder-cms/webflow/
- name: WordPress
  rows: 30
  url: /applications/website-builder-cms/wordpress/
sitemap: true
title: 'Payload: Website Builder, CMS & Blogging reference app'
---
