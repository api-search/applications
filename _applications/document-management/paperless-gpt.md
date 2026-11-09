---
app: paperless-gpt
app_slug: paperless-gpt
app_url: https://github.com/icereed/paperless-gpt
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Paperless-ngx
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: domain
  name: Hosted LLM Inference
  providers:
  - Google Gemini
  - Anthropic
  - OpenAI
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.30
  key: AE-110.10.30
  layer: domain
  name: Model Routing & Gateways
  providers:
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.40.20
  key: AE-110.40.20
  layer: domain
  name: OCR & Document AI
  providers:
  - Google Document AI
  - Azure Document Intelligence
  - Docling Server
  - Mistral AI
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: API Evangelist extension
  id: AE-110.10.40
  key: AE-110.10.40
  layer: domain
  name: On-Device & Edge Inference
  providers:
  - Ollama
  - LM Studio
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.10.20
  key: AE-110.10.20
  layer: domain
  name: OpenAI-Compatible Endpoints
  providers:
  - Azure OpenAI
  - Groq
  - Together
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: document-management
  name: Document Management & OCR
  url: /applications/document-management/
counts:
  declared: 11
  observed: 3
credits: []
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 49.3
    mcp: &id009
      status: none
    slug: google-cloud-document-ai
    status: profiled
    tags: &id010
    - Data Extraction
    - Document Processing
    - Forms
    - Google Cloud
    url: /providers/google-cloud-document-ai/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: strong
    in_catalog: true
    kin_score: 55.1
    mcp: &id011
      status: none
    slug: google-gemini
    status: profiled
    tags: &id012
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.4
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id019
      status: none
    slug: ollama
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id001
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id002
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 44.6
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 38.0
    mcp: &id007
      source: https://github.com/docling-project/docling-mcp
      status: verified
    slug: docling
    status: profiled
    tags: &id008
    - Documents
    - OCR
    - PDF
    - Parsing
    url: /providers/docling/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 21.6
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id013
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id014
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 18.2
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id015
      status: none
    slug: lm-studio
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Company
    - Local LLM
    - Machine Learning
    url: /providers/lm-studio/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id017
      status: none
    slug: mistral
    status: profiled
    tags: &id018
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
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
  facts:
    agent_band: agent-native
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
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
  facts:
    agent_band: agent-ready
    agent_readiness: 46.9
    band: strong
    in_catalog: true
    kin_score: 55.4
    mcp: &id023
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id024
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 1.3
    mcp: &id025
      status: none
    slug: paperless-ngx
    status: profiled
    tags: &id026
    - Company
    url: /providers/paperless-ngx/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.4
    band: thin
    in_catalog: true
    kin_score: 34.6
    mcp: &id027
      source: https://docs.together.ai/docs/mcp
      status: verified
    slug: together-ai
    status: profiled
    tags: &id028
    - Artificial Intelligence
    - Foundation Models
    - Inference
    - LLM
    url: /providers/together-ai/
  layer: domain
  name: Together
  provider: together-ai
  says: lists Together as an integration
  source: https://github.com/icereed/paperless-gpt
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/document-management/paperless-gpt/
providers:
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id001
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 51.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id003
  name: Azure Document Intelligence
  slug: microsoft-azure
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 44.6
  mcp: *id005
  name: Azure OpenAI
  slug: microsoft-azure-openai
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-openai/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id007
  name: Docling Server
  slug: docling
  status: profiled
  tags: *id008
  url: /providers/docling/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 49.3
  mcp: *id009
  name: Google Document AI
  slug: google-cloud-document-ai
  status: profiled
  tags: *id010
  url: /providers/google-cloud-document-ai/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id011
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id012
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.6
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id013
  name: Groq
  slug: groq
  status: profiled
  tags: *id014
  url: /providers/groq/
- agent_band: agent-aware
  agent_readiness: 18.2
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id015
  name: LM Studio
  slug: lm-studio
  status: profiled
  tags: *id016
  url: /providers/lm-studio/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id017
  name: Mistral AI
  slug: mistral
  status: profiled
  tags: *id018
  url: /providers/mistral/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 38.0
  mcp: *id019
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id020
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id021
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id022
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.9
  band: strong
  in_catalog: true
  kin_score: 55.4
  mcp: *id023
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id024
  url: /providers/openrouter/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 1.3
  mcp: *id025
  name: Paperless-ngx
  slug: paperless-ngx
  status: profiled
  tags: *id026
  url: /providers/paperless-ngx/
- agent_band: agent-ready
  agent_readiness: 40.4
  band: thin
  in_catalog: true
  kin_score: 34.6
  mcp: *id027
  name: Together
  slug: together-ai
  status: profiled
  tags: *id028
  url: /providers/together-ai/
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
- name: Paperless-ngx
  rows: 8
  url: /applications/document-management/paperless-ngx/
- name: Papra
  rows: 7
  url: /applications/document-management/papra/
- name: Stirling-PDF
  rows: 5
  url: /applications/document-management/stirling-pdf/
sitemap: true
title: 'paperless-gpt: Document Management & OCR reference app'
---
