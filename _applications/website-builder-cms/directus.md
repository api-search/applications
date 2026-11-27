---
app: Directus
app_slug: directus
app_url: https://github.com/directus/directus
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-170.30.10
  key: AE-170.30.10
  layer: domain
  name: Image Processing & Optimisation
  providers:
  - Cloudinary
  url: /capabilities/photo-image-libraries/
  via_parent: Photo & Image Libraries
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  - Supabase Storage
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-926
  key: AE-926
  layer: common
  name: Web Hosting & Control Panels
  providers:
  - Netlify
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Google Gemini
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: agent
  name: Observability Management
  providers:
  - Braintrust
  - Langfuse
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: website-builder-cms
  name: Website Builder, CMS & Blogging
  url: /applications/website-builder-cms/
counts:
  declared: 0
  observed: 12
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/directus/directus/blob/main/api/package.json
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
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
    mcp: &id003
      status: none
    slug: amazon-ses
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Email
    - Email Deliverability
    - Email Service
    url: /providers/amazon-ses/
  layer: common
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id008
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
  layer: common
  name: Azure Blob Storage
  provider: microsoft-azure-blob-storage
  says: ships the Azure Blob Storage SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    agent_readiness: 51.7
    band: developing
    in_catalog: true
    kin_score: 46.3
    mcp: &id009
      source: https://www.braintrust.dev/docs/integrations/developer-tools/mcp
      status: verified
    slug: braintrust
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Evaluation
    - LLM
    - Observability
    url: /providers/braintrust/
  layer: agent
  name: Braintrust
  provider: braintrust
  says: ships the Braintrust SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.30.10
    key: AE-170.30.10
    name: Image Processing & Optimisation
    url: /capabilities/photo-image-libraries/
    via_parent: Photo & Image Libraries
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: exemplar
    in_catalog: true
    kin_score: 82.0
    mcp: &id011
      source: https://cloudinary.com/documentation/cloudinary_llm_mcp
      status: verified
    slug: cloudinary
    status: profiled
    tags: &id012
    - Asset Management
    - Digital Asset Management
    - Image Processing
    - Image Transformation
    url: /providers/cloudinary/
  layer: domain
  name: Cloudinary
  provider: cloudinary
  says: ships the Cloudinary SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    mcp: &id013
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id014
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
  layer: common
  name: Google Cloud Storage
  provider: gcp-cloud-storage
  says: ships the Google Cloud Storage SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    mcp: &id015
      status: none
    slug: google-gemini
    status: profiled
    tags: &id016
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    agent_readiness: 35.9
    band: thin
    in_catalog: true
    kin_score: 36.5
    mcp: &id017
      source: https://github.com/langfuse/mcp-server-langfuse
      status: verified
    slug: langfuse
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - LLM
    - Observability
    - Open Source
    url: /providers/langfuse/
  layer: agent
  name: Langfuse
  provider: langfuse
  says: ships the Langfuse SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-926
    key: AE-926
    name: Web Hosting & Control Panels
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.9
    band: exemplar
    in_catalog: true
    kin_score: 72.2
    mcp: &id019
      source: https://github.com/netlify/netlify-mcp
      status: verified
    slug: netlify
    status: profiled
    tags: &id020
    - CDN
    - Cloud
    - Continuous Deployment
    - Developer Tools
    url: /providers/netlify/
  layer: common
  name: Netlify
  provider: netlify
  says: ships the Netlify SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    mcp: &id021
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
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
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 49.4
    mcp: &id023
      source: https://github.com/supabase/mcp
      status: verified
    slug: supabase
    status: profiled
    tags: &id024
    - Authentication
    - Backend-as-a-Service
    - Open Source
    - PostgreSQL
    url: /providers/supabase/
  layer: common
  name: Supabase Storage
  provider: supabase
  says: ships the Supabase Storage SDK or integration code
  source: https://github.com/directus/directus/blob/main/api/package.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/website-builder-cms/directus/
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
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
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
  agent_readiness: 37.9
  band: strong
  in_catalog: true
  kin_score: 66.3
  mcp: *id007
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id008
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-ready
  agent_readiness: 51.7
  band: developing
  in_catalog: true
  kin_score: 46.3
  mcp: *id009
  name: Braintrust
  slug: braintrust
  status: profiled
  tags: *id010
  url: /providers/braintrust/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id011
  name: Cloudinary
  slug: cloudinary
  status: profiled
  tags: *id012
  url: /providers/cloudinary/
- agent_band: agent-ready
  agent_readiness: 45.1
  band: exemplar
  in_catalog: true
  kin_score: 74.1
  mcp: *id013
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id014
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id015
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id016
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 35.9
  band: thin
  in_catalog: true
  kin_score: 36.5
  mcp: *id017
  name: Langfuse
  slug: langfuse
  status: profiled
  tags: *id018
  url: /providers/langfuse/
- agent_band: agent-ready
  agent_readiness: 58.9
  band: exemplar
  in_catalog: true
  kin_score: 72.2
  mcp: *id019
  name: Netlify
  slug: netlify
  status: profiled
  tags: *id020
  url: /providers/netlify/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id021
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id022
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 49.4
  mcp: *id023
  name: Supabase Storage
  slug: supabase
  status: profiled
  tags: *id024
  url: /providers/supabase/
siblings:
- name: Ghost
  rows: 76
  url: /applications/website-builder-cms/ghost/
- name: Payload
  rows: 9
  url: /applications/website-builder-cms/payload/
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
title: 'Directus: Website Builder, CMS & Blogging reference app'
---
