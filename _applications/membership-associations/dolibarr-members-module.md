---
app: Dolibarr (Members module)
app_slug: dolibarr-members-module
app_url: https://github.com/Dolibarr/dolibarr
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: domain
  name: Payment Processing Management
  providers:
  - Paypal
  - Stripe
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic (Claude)
  - Deepseek
  - Google Gemini
  - Groq
  - Mistral
  - OpenAI (ChatGPT)
  - Perplexity
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: membership-associations
  name: Membership & Association Management
  url: /applications/membership-associations/
counts:
  declared: 0
  observed: 10
credits: []
evidence:
- route: source code
  url: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
- route: source code
  url: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs
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
  name: Anthropic (Claude)
  provider: anthropic
  says: ships the Anthropic (Claude) SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
    mcp: &id003
      status: none
    slug: deepseek
    status: profiled
    tags: &id004
    - Artificial Intelligence
    - Chat
    - Chat Completions
    - LLM
    url: /providers/deepseek/
  layer: agent
  name: Deepseek
  provider: deepseek
  says: ships the Deepseek SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
    mcp: &id005
      status: none
    slug: google-gemini
    status: profiled
    tags: &id006
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: ships the Google Gemini SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
    mcp: &id007
      source: https://github.com/groq/groq-mcp-server
      status: verified
    slug: groq
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Inference
    - LLM
    - LPU
    url: /providers/groq/
  layer: agent
  name: Groq
  provider: groq
  says: ships the Groq SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
    agent_readiness: 28.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id009
      status: none
    slug: mistral
    status: profiled
    tags: &id010
    - Agents
    - Embeddings
    - Machine Learning
    - OCR
    url: /providers/mistral/
  layer: agent
  name: Mistral
  provider: mistral
  says: ships the Mistral SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
  name: OpenAI (ChatGPT)
  provider: openai
  says: ships the OpenAI (ChatGPT) SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
    agent_band: agent-ready
    agent_readiness: 36.3
    band: strong
    in_catalog: true
    kin_score: 54.9
    mcp: &id013
      source: https://developer.paypal.com/tools/mcp-server/
      status: verified
    slug: paypal
    status: profiled
    tags: &id014
    - Billing
    - Commerce
    - Disputes
    - PayPal
    url: /providers/paypal/
  layer: domain
  name: Paypal
  provider: paypal
  says: ships the Paypal SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/paypal
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
    agent_readiness: 66.6
    band: strong
    in_catalog: true
    kin_score: 65.7
    mcp: &id015
      source: https://github.com/perplexityai/modelcontextprotocol
      status: verified
    slug: perplexity
    status: profiled
    tags: &id016
    - Agents
    - Artificial Intelligence
    - LLM
    - Search
    url: /providers/perplexity/
  layer: agent
  name: Perplexity
  provider: perplexity
  says: ships the Perplexity SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/blob/develop/htdocs/ai/lib/ai.lib.php
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
    mcp: &id017
      source: https://docs.stripe.com/mcp
      status: verified
    slug: stripe
    status: profiled
    tags: &id018
    - Commerce
    - Financial Services
    - Fintech
    - Payments
    url: /providers/stripe/
  layer: domain
  name: Stripe
  provider: stripe
  says: ships the Stripe SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/stripe
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id019
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id020
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: ships the Zapier SDK or integration code
  source: https://github.com/Dolibarr/dolibarr/tree/develop/htdocs/zapier
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/membership-associations/dolibarr-members-module/
providers:
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id001
  name: Anthropic (Claude)
  slug: anthropic
  status: profiled
  tags: *id002
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: developing
  in_catalog: true
  kin_score: 41.2
  mcp: *id003
  name: Deepseek
  slug: deepseek
  status: profiled
  tags: *id004
  url: /providers/deepseek/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id005
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id006
  url: /providers/google-gemini/
- agent_band: agent-aware
  agent_readiness: 21.2
  band: thin
  in_catalog: true
  kin_score: 32.3
  mcp: *id007
  name: Groq
  slug: groq
  status: profiled
  tags: *id008
  url: /providers/groq/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id009
  name: Mistral
  slug: mistral
  status: profiled
  tags: *id010
  url: /providers/mistral/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id011
  name: OpenAI (ChatGPT)
  slug: openai
  status: profiled
  tags: *id012
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: strong
  in_catalog: true
  kin_score: 54.9
  mcp: *id013
  name: Paypal
  slug: paypal
  status: profiled
  tags: *id014
  url: /providers/paypal/
- agent_band: agent-native
  agent_readiness: 66.6
  band: strong
  in_catalog: true
  kin_score: 65.7
  mcp: *id015
  name: Perplexity
  slug: perplexity
  status: profiled
  tags: *id016
  url: /providers/perplexity/
- agent_band: agent-native
  agent_readiness: 57.6
  band: exemplar
  in_catalog: true
  kin_score: 82.0
  mcp: *id017
  name: Stripe
  slug: stripe
  status: profiled
  tags: *id018
  url: /providers/stripe/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id019
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id020
  url: /providers/zapier/
siblings:
- name: Galette
  rows: 4
  url: /applications/membership-associations/galette/
- name: Glue Up
  rows: 14
  url: /applications/membership-associations/glue-up/
- name: Novi AMS
  rows: 46
  url: /applications/membership-associations/novi-ams/
- name: Paid Memberships Pro
  rows: 29
  url: /applications/membership-associations/paid-memberships-pro/
- name: WildApricot
  rows: 8
  url: /applications/membership-associations/wildapricot/
sitemap: true
title: 'Dolibarr (Members module): Membership & Association Management reference app'
---
