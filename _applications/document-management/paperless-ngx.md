---
app: Paperless-ngx
app_slug: paperless-ngx
app_url: https://github.com/paperless-ngx/paperless-ngx
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-918
  key: AE-918
  layer: domain
  name: Document Generation & Conversion
  providers:
  - Apache Tika
  - Gotenberg
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-110.60.10
  key: AE-110.60.10
  layer: domain
  name: Embeddings
  providers:
  - Hugging Face
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: domain
  name: OCR & Document AI
  providers:
  - Azure AI Document Intelligence
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: domain
  name: On-Device & Edge Inference
  providers:
  - Ollama
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
category:
  id: document-management
  name: Document Management & OCR
  url: /applications/document-management/
counts:
  declared: 2
  observed: 6
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: thin
    in_catalog: true
    kin_score: 34.2
    mcp: &id001
      status: none
    slug: apache-tika
    status: profiled
    tags: &id002
    - Content Extraction
    - Document Processing
    - Metadata
    - Text Extraction
    url: /providers/apache-tika/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 51.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: emerging
    in_catalog: true
    kin_score: 20.2
    mcp: &id007
      status: none
    slug: gotenberg
    status: profiled
    tags: &id008
    - Conversion
    - Docker
    - Open Source
    - PDF
    url: /providers/gotenberg/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id009
      source: https://github.com/huggingface/hf-mcp-server
      status: verified
    slug: hugging-face
    status: profiled
    tags: &id010
    - Computer Vision
    - Embeddings
    - Image Generation
    - LLM
    url: /providers/hugging-face/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id011
      status: none
    slug: ollama
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id013
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id005
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id006
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id016
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Outlook
  provider: microsoft-outlook
  says: lists Outlook as an integration
  source: https://github.com/paperless-ngx/paperless-ngx/blob/dev/docs/configuration.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/document-management/paperless-ngx/
providers:
- agent_band: agent-aware
  agent_readiness: 17.2
  band: thin
  in_catalog: true
  kin_score: 34.2
  mcp: *id001
  name: Apache Tika
  slug: apache-tika
  status: profiled
  tags: *id002
  url: /providers/apache-tika/
- agent_band: agent-ready
  agent_readiness: 51.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id003
  name: Azure AI Document Intelligence
  slug: microsoft-azure
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id005
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id006
  url: /providers/google-gmail/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: emerging
  in_catalog: true
  kin_score: 20.2
  mcp: *id007
  name: Gotenberg
  slug: gotenberg
  status: profiled
  tags: *id008
  url: /providers/gotenberg/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id009
  name: Hugging Face
  slug: hugging-face
  status: profiled
  tags: *id010
  url: /providers/hugging-face/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id011
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id012
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id013
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id014
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id015
  name: Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id016
  url: /providers/microsoft-outlook/
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
- name: Papra
  rows: 7
  url: /applications/document-management/papra/
- name: Stirling-PDF
  rows: 5
  url: /applications/document-management/stirling-pdf/
sitemap: true
title: 'Paperless-ngx: Document Management & OCR reference app'
---
