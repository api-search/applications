---
app: JobSync
app_slug: jobsync
app_url: https://github.com/Gsync/jobsync
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-230.120
  key: AE-230.120
  layer: domain
  name: Job Listings Search & Aggregation
  providers:
  - Greenhouse Job Board
  - Lever Postings
  url: /capabilities/job-listings-search-aggregation/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - OpenObserve
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - DeepSeek
  - Google Gemini
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
  declared: 2
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Gsync/jobsync/blob/main/package.json
- route: documentation
  url: https://github.com/Gsync/jobsync/blob/main/README.md
- route: source code
  url: https://github.com/Gsync/jobsync/blob/main/.env.example
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
    agent_band: agent-aware
    agent_readiness: 22.4
    band: developing
    in_catalog: true
    kin_score: 41.2
    mcp: &id001
      status: none
    slug: deepseek
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: agent
  name: DeepSeek
  provider: deepseek
  says: ships the DeepSeek SDK or integration code
  source: https://github.com/Gsync/jobsync/blob/main/package.json
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
    mcp: &id003
      status: none
    slug: google-gemini
    status: profiled
    tags: &id004
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/Gsync/jobsync/blob/main/package.json
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
    mcp: &id009
      status: none
    slug: ollama
    status: profiled
    tags: &id010
    - Artificial Intelligence
    - LLM
    - Models
    - Ollama
    url: /providers/ollama/
  layer: agent
  name: Ollama
  provider: ollama
  says: ships the Ollama SDK or integration code
  source: https://github.com/Gsync/jobsync/blob/main/package.json
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
    mcp: &id011
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id012
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI
  provider: openai
  says: ships the OpenAI SDK or integration code
  source: https://github.com/Gsync/jobsync/blob/main/package.json
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
    agent_readiness: 45.5
    band: developing
    in_catalog: true
    kin_score: 41.6
    mcp: &id013
      source: https://openobserve.ai/docs/integration/ai/mcp/
      status: verified
    slug: openobserve
    status: profiled
    tags: &id014
    - Logs
    - Metrics
    - Observability
    - Traces
    url: /providers/openobserve/
  layer: common
  name: OpenObserve
  provider: openobserve
  says: ships the OpenObserve SDK or integration code
  source: https://github.com/Gsync/jobsync/blob/main/.env.example
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
  source: https://github.com/Gsync/jobsync/blob/main/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 60.3
    band: exemplar
    in_catalog: true
    kin_score: 77.9
    mcp: &id005
      status: none
    slug: greenhouse
    status: profiled
    tags: &id006
    - Applicant Tracking
    - Greenhouse
    - Human Resources
    - Recruiting
    url: /providers/greenhouse/
  layer: domain
  name: Greenhouse Job Board
  provider: greenhouse
  says: lists Greenhouse Job Board as an integration
  source: https://github.com/Gsync/jobsync/blob/main/README.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-230.120
    key: AE-230.120
    name: Job Listings Search & Aggregation
    url: /capabilities/job-listings-search-aggregation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.5
    band: strong
    in_catalog: true
    kin_score: 55.0
    mcp: &id007
      status: unknown
    slug: lever
    status: profiled
    tags: &id008
    - Applicant Tracking
    - Human Resources
    - Recruiting
    - Talent Acquisition
    url: /providers/lever/
  layer: domain
  name: Lever Postings
  provider: lever
  says: lists Lever Postings as an integration
  source: https://github.com/Gsync/jobsync/blob/main/README.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/job-search/jobsync/
providers:
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id001
  name: DeepSeek
  slug: deepseek
  status: profiled
  tags: *id002
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id003
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id004
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 60.3
  band: exemplar
  in_catalog: true
  kin_score: 77.9
  mcp: *id005
  name: Greenhouse Job Board
  slug: greenhouse
  status: profiled
  tags: *id006
  url: /providers/greenhouse/
- agent_band: agent-ready
  agent_readiness: 39.5
  band: strong
  in_catalog: true
  kin_score: 55.0
  mcp: *id007
  name: Lever Postings
  slug: lever
  status: profiled
  tags: *id008
  url: /providers/lever/
- agent_band: agent-aware
  agent_readiness: 24.4
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id009
  name: Ollama
  slug: ollama
  status: profiled
  tags: *id010
  url: /providers/ollama/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id011
  name: OpenAI
  slug: openai
  status: profiled
  tags: *id012
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 45.5
  band: developing
  in_catalog: true
  kin_score: 41.6
  mcp: *id013
  name: OpenObserve
  slug: openobserve
  status: profiled
  tags: *id014
  url: /providers/openobserve/
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
- name: LinkedIn
  rows: 7
  url: /applications/job-search/linkedin/
- name: Reactive Resume
  rows: 30
  url: /applications/job-search/reactive-resume/
- name: Resume Matcher
  rows: 8
  url: /applications/job-search/resume-matcher/
sitemap: true
title: 'JobSync: Job Search reference app'
---
