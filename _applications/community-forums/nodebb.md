---
app: NodeBB
app_slug: nodebb
app_url: https://github.com/NodeBB/NodeBB
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: domain
  name: Bot Protection & CAPTCHA
  providers:
  - Akismet
  - Cloudflare Turnstile
  - Google reCAPTCHA
  - hCaptcha
  - Project Honey Pot
  - StopForumSpam
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - MongoDB
  - PostgreSQL
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
category:
  id: community-forums
  name: Community & Forums
  url: /applications/community-forums/
counts:
  declared: 0
  observed: 9
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
- route: source code
  url: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id001
      status: unchecked
    slug: akismet
    status: queued for profiling
    tags: &id002 []
    url: null
  layer: domain
  name: Akismet
  provider: akismet
  says: ships the Akismet SDK or integration code
  source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
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
    agent_readiness: 23.1
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id003
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id004
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
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
    agent_readiness: 24.6
    band: developing
    in_catalog: true
    kin_score: 48.1
    mcp: &id005
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id006
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Google reCAPTCHA
  provider: google-recaptcha
  says: ships the Google reCAPTCHA SDK or integration code
  source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 31.5
    mcp: &id007
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id008
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
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
    agent_readiness: 56.0
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id009
      source: https://github.com/mongodb-js/mongodb-mcp-server
      status: verified
    slug: mongodb
    status: profiled
    tags: &id010
    - Cloud Database
    - Database
    - Document Database
    - NoSQL
    url: /providers/mongodb/
  layer: common
  name: MongoDB
  provider: mongodb
  says: ships the MongoDB SDK or integration code
  source: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
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
    agent_band: human-only
    agent_readiness: 0.6
    band: emerging
    in_catalog: true
    kin_score: 12.2
    mcp: &id011
      status: none
    slug: postgresql
    status: profiled
    tags: &id012
    - Database
    - Open Source
    - Relational Database
    - SQL
    url: /providers/postgresql/
  layer: common
  name: PostgreSQL
  provider: postgresql
  says: ships the PostgreSQL SDK or integration code
  source: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
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
    agent_readiness: 7.9
    band: emerging
    in_catalog: true
    kin_score: 17.6
    mcp: &id013
      status: unknown
    slug: project-honeypot
    status: profiled
    tags: &id014
    - Anti-Spam
    - Community
    - Fraud Prevention
    - Security
    url: /providers/project-honeypot/
  layer: domain
  name: Project Honey Pot
  provider: project-honeypot
  says: ships the Project Honey Pot SDK or integration code
  source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
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
    agent_band: agent-native
    agent_readiness: 49.8
    band: developing
    in_catalog: true
    kin_score: 47.4
    mcp: &id015
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id016
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://raw.githubusercontent.com/NodeBB/NodeBB/master/install/package.json
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.8
    mcp: &id017
      status: unknown
    slug: stopforumspam
    status: profiled
    tags: &id018
    - Community
    - Company
    - Security
    - Spam
    url: /providers/stopforumspam/
  layer: domain
  name: StopForumSpam
  provider: stopforumspam
  says: ships the StopForumSpam SDK or integration code
  source: https://raw.githubusercontent.com/akhoury/nodebb-plugin-spam-be-gone/master/library.js
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/community-forums/nodebb/
providers:
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id001
  name: Akismet
  slug: akismet
  status: queued for profiling
  tags: *id002
  url: null
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id003
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id004
  url: /providers/cloudflare-turnstile/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: developing
  in_catalog: true
  kin_score: 48.1
  mcp: *id005
  name: Google reCAPTCHA
  slug: google-recaptcha
  status: profiled
  tags: *id006
  url: /providers/google-recaptcha/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id007
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id008
  url: /providers/hcaptcha/
- agent_band: agent-ready
  agent_readiness: 56.0
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id009
  name: MongoDB
  slug: mongodb
  status: profiled
  tags: *id010
  url: /providers/mongodb/
- agent_band: human-only
  agent_readiness: 0.6
  band: emerging
  in_catalog: true
  kin_score: 12.2
  mcp: *id011
  name: PostgreSQL
  slug: postgresql
  status: profiled
  tags: *id012
  url: /providers/postgresql/
- agent_band: agent-aware
  agent_readiness: 7.9
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id013
  name: Project Honey Pot
  slug: project-honeypot
  status: profiled
  tags: *id014
  url: /providers/project-honeypot/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id015
  name: Redis
  slug: redis
  status: profiled
  tags: *id016
  url: /providers/redis/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.8
  mcp: *id017
  name: StopForumSpam
  slug: stopforumspam
  status: profiled
  tags: *id018
  url: /providers/stopforumspam/
siblings:
- name: Circle
  rows: 36
  url: /applications/community-forums/circle/
- name: Discourse
  rows: 44
  url: /applications/community-forums/discourse/
- name: Flarum
  rows: 4
  url: /applications/community-forums/flarum/
- name: Lemmy
  rows: 2
  url: /applications/community-forums/lemmy/
- name: Mastodon
  rows: 10
  url: /applications/community-forums/mastodon/
sitemap: true
title: 'NodeBB: Community & Forums reference app'
---
