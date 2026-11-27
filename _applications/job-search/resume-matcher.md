---
app: Resume Matcher
app_slug: resume-matcher
app_url: https://github.com/srbhr/Resume-Matcher
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic
  - Azure AI Foundry
  - DeepSeek
  - Google Gemini
  - Groq
  - OpenAI
  - OpenRouter
  url: /capabilities/model-inference/
  via_parent: Model Inference
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
  id: job-search
  name: Job Search
  url: /applications/job-search/
counts:
  declared: 0
  observed: 8
credits: []
evidence:
- route: source code
  url: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
integrations:
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
  layer: agent
  name: Anthropic
  provider: anthropic
  says: ships the Anthropic SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
    mcp: &id003
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-openai
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Embeddings
    - GPT
    - Generative AI
    url: /providers/microsoft-azure-openai/
  layer: agent
  name: Azure AI Foundry
  provider: microsoft-azure-openai
  says: ships the Azure AI Foundry SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
    agent_band: agent-aware
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id005
      status: none
    slug: deepseek
    status: profiled
    tags: &id006
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: agent
  name: DeepSeek
  provider: deepseek
  says: ships the DeepSeek SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
    mcp: &id007
      status: none
    slug: google-gemini
    status: profiled
    tags: &id008
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
    agent_band: agent-aware
    agent_readiness: 21.2
    band: thin
    in_catalog: true
    kin_score: 32.3
    mcp: &id009
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
  layer: agent
  name: Groq
  provider: groq
  says: ships the Groq SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
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
    agent_readiness: 46.4
    band: strong
    in_catalog: true
    kin_score: 54.8
    mcp: &id015
      source: https://openrouter.ai/docs/guides/overview/mcp-server
      status: verified
    slug: openrouter
    status: profiled
    tags: &id016
    - Artificial Intelligence
    - Gateways
    - LLM
    - Router
    url: /providers/openrouter/
  layer: agent
  name: OpenRouter
  provider: openrouter
  says: ships the OpenRouter SDK or integration code
  source: https://github.com/srbhr/Resume-Matcher/blob/main/apps/backend/.env.example
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/job-search/resume-matcher/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id001
  name: Anthropic
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 29.9
  band: exemplar
  in_catalog: true
  kin_score: 68.3
  mcp: *id003
  name: Azure AI Foundry
  slug: microsoft-azure-openai
  status: profiled
  tags: *id004
  url: /providers/microsoft-azure-openai/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id005
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id006
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id007
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id008
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id009
  name: Groq
  slug: groq
  status: profiled
  tags: *id010
  url: /providers/groq/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id011
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id012
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id013
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id014
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 46.4
  band: strong
  in_catalog: true
  kin_score: 54.8
  mcp: *id015
  name: OpenRouter
  slug: openrouter
  status: profiled
  tags: *id016
  url: /providers/openrouter/
siblings:
- name: Glassdoor
  rows: 2
  url: /applications/job-search/glassdoor/
- name: Indeed
  rows: 2
  url: /applications/job-search/indeed/
- name: JobSpy
  rows: 9
  url: /applications/job-search/jobspy/
- name: JobSync
  rows: 8
  url: /applications/job-search/jobsync/
- name: LinkedIn
  rows: 7
  url: /applications/job-search/linkedin/
- name: Reactive Resume
  rows: 30
  url: /applications/job-search/reactive-resume/
sitemap: true
title: 'Resume Matcher: Job Search reference app'
---
