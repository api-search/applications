---
app: PawSome AI
app_slug: pawsome-ai
app_url: https://github.com/MohammedMusharraf11/PawSome-AI
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Google Gemini
  url: /capabilities/model-inference/
  via_parent: Model Inference
- attribution: API Evangelist extension
  id: AE-110.60.20
  key: AE-110.60.20
  layer: agent
  name: Vector Search
  providers:
  - Chroma
  url: /capabilities/retrieval-embeddings/
  via_parent: Retrieval & Embeddings
category:
  id: pet-care
  name: Pet Care
  url: /applications/pet-care/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-110.60.20
    key: AE-110.60.20
    name: Vector Search
    url: /capabilities/retrieval-embeddings/
    via_parent: Retrieval & Embeddings
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.1
    band: strong
    in_catalog: true
    kin_score: 58.5
    mcp: &id001
      source: https://github.com/chroma-core/chroma-mcp
      status: verified
    slug: chroma
    status: profiled
    tags: &id002
    - AI-native
    - Apache 2.0
    - Artificial Intelligence
    - Cloud
    url: /providers/chroma/
  layer: agent
  name: Chroma
  provider: chroma
  says: ships the Chroma SDK or integration code
  source: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
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
  source: https://github.com/MohammedMusharraf11/PawSome-AI/blob/main/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pet-care/pawsome-ai/
providers:
- agent_band: agent-ready
  agent_readiness: 40.1
  band: strong
  in_catalog: true
  kin_score: 58.5
  mcp: *id001
  name: Chroma
  slug: chroma
  status: profiled
  tags: *id002
  url: /providers/chroma/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: strong
  in_catalog: true
  kin_score: 55.1
  mcp: *id003
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id004
  url: /providers/google-gemini/
siblings:
- name: Chewy
  rows: 4
  url: /applications/pet-care/chewy/
- name: Fi Smart Collar
  rows: 4
  url: /applications/pet-care/fi-smart-collar/
- name: oh-my-petcare
  rows: 2
  url: /applications/pet-care/oh-my-petcare/
- name: PetDesk
  rows: 10
  url: /applications/pet-care/petdesk/
- name: PETLIBRO
  rows: 10
  url: /applications/pet-care/petlibro/
- name: Rover
  rows: 10
  url: /applications/pet-care/rover/
- name: Tractive
  rows: 7
  url: /applications/pet-care/tractive/
sitemap: true
title: 'PawSome AI: Pet Care reference app'
---
