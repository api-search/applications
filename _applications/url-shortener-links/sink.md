---
app: Sink
app_slug: sink
app_url: https://github.com/ccbikai/Sink
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Cloudflare Analytics Engine
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Cloudflare Workers KV/D1
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Cloudflare R2
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Cloudflare Access
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Cloudflare Workers AI
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: url-shortener-links
  name: Link Management & URL Shorteners
  url: /applications/url-shortener-links/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: source code
  url: https://github.com/ccbikai/Sink/blob/master/.env.example
- route: source code
  url: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-native
    agent_readiness: 69.4
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id002
      source: https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/
      status: verified
    slug: cloudflare
    status: profiled
    tags: &id003
    - AI Gateway
    - API Gateway
    - Artificial Intelligence
    - CDN
    url: /providers/cloudflare/
  layer: common
  name: Cloudflare Access
  provider: cloudflare
  says: ships the Cloudflare Access SDK or integration code
  source: https://github.com/ccbikai/Sink/blob/master/.env.example
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Cloudflare Analytics Engine
  provider: cloudflare
  says: ships the Cloudflare Analytics Engine SDK or integration code
  source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: *id001
  layer: common
  name: Cloudflare R2
  provider: cloudflare
  says: ships the Cloudflare R2 SDK or integration code
  source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts: *id001
  layer: agent
  name: Cloudflare Workers AI
  provider: cloudflare
  says: ships the Cloudflare Workers AI SDK or integration code
  source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-915
    key: AE-915
    name: Managed Operational Databases
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts: *id001
  layer: common
  name: Cloudflare Workers KV/D1
  provider: cloudflare
  says: ships the Cloudflare Workers KV/D1 SDK or integration code
  source: https://github.com/ccbikai/Sink/blob/master/wrangler.jsonc
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/url-shortener-links/sink/
providers:
- agent_band: agent-native
  agent_readiness: 69.4
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id002
  name: Cloudflare Access
  slug: cloudflare
  status: profiled
  tags: *id003
  url: /providers/cloudflare/
siblings:
- name: Bitly
  rows: 55
  url: /applications/url-shortener-links/bitly/
- name: Dub
  rows: 25
  url: /applications/url-shortener-links/dub/
- name: Kutt
  rows: 1
  url: /applications/url-shortener-links/kutt/
- name: Shlink
  rows: 6
  url: /applications/url-shortener-links/shlink/
- name: Short.io
  rows: 8
  url: /applications/url-shortener-links/short-io/
- name: YOURLS
  rows: 2
  url: /applications/url-shortener-links/yourls/
sitemap: true
title: 'Sink: Link Management & URL Shorteners reference app'
---
