---
app: Pixelfed
app_slug: pixelfed
app_url: https://github.com/pixelfed/pixelfed
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Cloudflare Turnstile
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-915
  key: AE-915
  layer: common
  name: Managed Operational Databases
  providers:
  - MySQL
  - Redis
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Expo push
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.70
  key: AE-150.70
  layer: common
  name: Realtime Messaging
  providers:
  - Pusher
  url: /capabilities/realtime-messaging/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: common
  name: Storage Management
  providers:
  - Amazon S3
  - DigitalOcean Spaces
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Amazon SES
  - Mailgun
  - Resend
  url: /capabilities/email/
  via_parent: Email
category:
  id: social-network
  name: Social Networking & Microblogging
  url: /applications/social-network/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
- route: source code
  url: https://github.com/pixelfed/pixelfed/blob/dev/.env.example
- route: source code
  url: https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
- route: source code
  url: https://github.com/pixelfed/pixelfed/blob/dev/config/filesystems.php
- route: source code
  url: https://github.com/pixelfed/pixelfed/blob/dev/config/services.php
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
    agent_band: agent-aware
    agent_readiness: 23.3
    band: exemplar
    in_catalog: true
    kin_score: 71.2
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
  source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
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
    agent_readiness: 39.4
    band: exemplar
    in_catalog: true
    kin_score: 80.6
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
  source: https://github.com/pixelfed/pixelfed/blob/dev/config/services.php
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
    mcp: &id005
      source: https://github.com/cloudflare/mcp
      status: verified
    slug: cloudflare-turnstile
    status: profiled
    tags: &id006
    - Bot Defense
    - CAPTCHA
    - Cloudflare
    - Turnstile
    url: /providers/cloudflare-turnstile/
  layer: common
  name: Cloudflare Turnstile
  provider: cloudflare-turnstile
  says: ships the Cloudflare Turnstile SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
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
    agent_readiness: 44.6
    band: developing
    in_catalog: true
    kin_score: 45.0
    mcp: &id007
      source: https://docs.digitalocean.com/reference/mcp/
      status: verified
    slug: digital-ocean
    status: profiled
    tags: &id008
    - Cloud
    - Compute
    - Infrastructure
    - Servers
    url: /providers/digital-ocean/
  layer: common
  name: DigitalOcean Spaces
  provider: digital-ocean
  says: ships the DigitalOcean Spaces SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/config/filesystems.php
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id009
      source: https://github.com/expo/expo-mcp
      status: verified
    slug: expo
    status: profiled
    tags: &id010
    - Build Automation
    - Mobile Development
    - Over-the-Air Updates
    - React Native
    url: /providers/expo/
  layer: common
  name: Expo push
  provider: expo
  says: ships the Expo push SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
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
    mcp: &id011
      status: none
    slug: hcaptcha
    status: profiled
    tags: &id012
    - Bot Defense
    - CAPTCHA
    - Privacy
    - hCaptcha
    url: /providers/hcaptcha/
  layer: common
  name: hCaptcha
  provider: hcaptcha
  says: ships the hCaptcha SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/config/captcha.php
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
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 32.6
    mcp: &id013
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id014
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
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
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 31.8
    mcp: &id015
      status: none
    slug: mysql
    status: profiled
    tags: &id016
    - Database
    - Open Source
    - RDBMS
    - Relational Database
    url: /providers/mysql/
  layer: common
  name: MySQL
  provider: mysql
  says: ships the MySQL SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/.env.example
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.70
    key: AE-150.70
    name: Realtime Messaging
    url: /capabilities/realtime-messaging/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.7
    band: thin
    in_catalog: true
    kin_score: 38.6
    mcp: &id017
      status: none
    slug: pusher
    status: profiled
    tags: &id018
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
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
    mcp: &id019
      source: https://github.com/redis/mcp-redis
      status: verified
    slug: redis
    status: profiled
    tags: &id020
    - Cache
    - Database
    - In-Memory
    - Key-Value Store
    url: /providers/redis/
  layer: common
  name: Redis
  provider: redis
  says: ships the Redis SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/.env.example
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
    agent_readiness: 49.4
    band: strong
    in_catalog: true
    kin_score: 58.9
    mcp: &id021
      source: https://resend.com/docs/mcp-server
      status: verified
    slug: resend
    status: profiled
    tags: &id022
    - Developer Tools
    - Email
    - Marketing Email
    - Transactional Email
    url: /providers/resend/
  layer: common
  name: Resend
  provider: resend
  says: ships the Resend SDK or integration code
  source: https://github.com/pixelfed/pixelfed/blob/dev/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/social-network/pixelfed/
providers:
- agent_band: agent-aware
  agent_readiness: 23.3
  band: exemplar
  in_catalog: true
  kin_score: 71.2
  mcp: *id001
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id002
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 39.4
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
- agent_band: agent-aware
  agent_readiness: 23.1
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id005
  name: Cloudflare Turnstile
  slug: cloudflare-turnstile
  status: profiled
  tags: *id006
  url: /providers/cloudflare-turnstile/
- agent_band: agent-ready
  agent_readiness: 44.6
  band: developing
  in_catalog: true
  kin_score: 45.0
  mcp: *id007
  name: DigitalOcean Spaces
  slug: digital-ocean
  status: profiled
  tags: *id008
  url: /providers/digital-ocean/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id009
  name: Expo push
  slug: expo
  status: profiled
  tags: *id010
  url: /providers/expo/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 31.5
  mcp: *id011
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id012
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id013
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id014
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 31.8
  mcp: *id015
  name: MySQL
  slug: mysql
  status: profiled
  tags: *id016
  url: /providers/mysql/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id017
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id018
  url: /providers/pusher/
- agent_band: agent-native
  agent_readiness: 49.8
  band: developing
  in_catalog: true
  kin_score: 47.4
  mcp: *id019
  name: Redis
  slug: redis
  status: profiled
  tags: *id020
  url: /providers/redis/
- agent_band: agent-ready
  agent_readiness: 49.4
  band: strong
  in_catalog: true
  kin_score: 58.9
  mcp: *id021
  name: Resend
  slug: resend
  status: profiled
  tags: *id022
  url: /providers/resend/
siblings:
- name: Bluesky
  rows: 4
  url: /applications/social-network/bluesky/
- name: Friendica
  rows: 20
  url: /applications/social-network/friendica/
- name: Instagram
  rows: 2
  url: /applications/social-network/instagram/
- name: Mastodon
  rows: 9
  url: /applications/social-network/mastodon/
- name: Misskey
  rows: 11
  url: /applications/social-network/misskey/
- name: Threads
  rows: 2
  url: /applications/social-network/threads/
sitemap: true
title: 'Pixelfed: Social Networking & Microblogging reference app'
---
