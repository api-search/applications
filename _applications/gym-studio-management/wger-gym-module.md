---
app: wger (gym module)
app_slug: wger-gym-module
app_url: https://github.com/wger-project/wger
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-130.30.10
  key: AE-130.30.10
  layer: domain
  name: Food Composition Databases
  providers:
  - Open Food Facts
  url: /capabilities/nutrition-food-data/
  via_parent: Nutrition & Food Data
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Google reCAPTCHA
  - Cloudflare Turnstile
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Prometheus
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: gym-studio-management
  name: Gym & Fitness Studio Management
  url: /applications/gym-studio-management/
counts:
  declared: 1
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/de.wger.flutter/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
- route: source code
  url: https://github.com/wger-project/wger/tree/master/wger/gym
- route: source code
  url: https://raw.githubusercontent.com/wger-project/docker/master/config/prod.env
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.9
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id003
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id004
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-130.30.10
    key: AE-130.30.10
    name: Food Composition Databases
    url: /capabilities/nutrition-food-data/
    via_parent: Nutrition & Food Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 66.2
    mcp: &id005
      status: none
    slug: open-food-facts
    status: profiled
    tags: &id006
    - Food
    - Nutrition
    - Open Data
    - Product Data
    url: /providers/open-food-facts/
  layer: domain
  name: Open Food Facts
  provider: open-food-facts
  says: ships the Open Food Facts SDK or integration code
  source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
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
    agent_band: agent-aware
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id007
      source: https://github.com/prometheus/prometheus-mcp
      status: verified
    slug: prometheus-io
    status: profiled
    tags: &id008
    - Metrics
    - Monitoring
    - Observability
    - Prometheus
    url: /providers/prometheus-io/
  layer: common
  name: Prometheus
  provider: prometheus-io
  says: ships the Prometheus SDK or integration code
  source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
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
    agent_readiness: 41.5
    band: developing
    in_catalog: true
    kin_score: 46.5
    mcp: &id009
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id010
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://raw.githubusercontent.com/wger-project/wger/master/pyproject.toml
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.70
    key: AE-160.70
    name: Bot Protection & CAPTCHA
    url: /capabilities/bot-protection-captcha/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: thin
    in_catalog: true
    kin_score: 28.8
    mcp: &id001
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id002
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: lists Cloudflare Turnstile as an integration
  source: https://raw.githubusercontent.com/wger-project/docker/master/config/prod.env
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/gym-studio-management/wger-gym-module/
providers:
- agent_band: agent-aware
  agent_readiness: 24.2
  band: thin
  in_catalog: true
  kin_score: 28.8
  mcp: *id001
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id002
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id003
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id004
  url: /providers/google-recaptcha/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id005
  name: Open Food Facts
  slug: open-food-facts
  status: profiled
  tags: *id006
  url: /providers/open-food-facts/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id007
  name: Prometheus
  slug: prometheus-io
  status: profiled
  tags: *id008
  url: /providers/prometheus-io/
- agent_band: agent-ready
  agent_readiness: 41.5
  band: developing
  in_catalog: true
  kin_score: 46.5
  mcp: *id009
  name: Redis
  slug: redis
  status: profiled
  tags: *id010
  url: /providers/redis/
siblings:
- name: GYM One
  rows: 4
  url: /applications/gym-studio-management/gym-one/
- name: Mindbody
  rows: 24
  url: /applications/gym-studio-management/mindbody/
- name: TeamUp
  rows: 2
  url: /applications/gym-studio-management/teamup/
- name: Wodify
  rows: 19
  url: /applications/gym-studio-management/wodify/
- name: Zen Planner
  rows: 21
  url: /applications/gym-studio-management/zen-planner/
sitemap: true
title: 'wger (gym module): Gym & Fitness Studio Management reference app'
---
