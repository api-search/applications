---
app: Flarum
app_slug: flarum
app_url: https://github.com/flarum/framework
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: domain
  name: Bot Protection & CAPTCHA
  providers:
  - Akismet
  url: /capabilities/bot-protection-captcha/
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
- attribution: API Evangelist extension
  id: AE-150.10.10
  key: AE-150.10.10
  layer: common
  name: Transactional Email
  providers:
  - Mailgun
  - Postmark
  url: /capabilities/email/
  via_parent: Email
category:
  id: community-forums
  name: Community & Forums
  url: /applications/community-forums/
counts:
  declared: 0
  observed: 4
credits: []
evidence:
- route: source code
  url: https://github.com/flarum/framework/tree/main/extensions
- route: source code
  url: https://github.com/flarum/framework/tree/main/framework/core/src/Mail
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
  source: https://github.com/flarum/framework/tree/main/extensions
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
    mcp: &id003
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id004
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/flarum/framework/tree/main/framework/core/src/Mail
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
    agent_readiness: 41.7
    band: exemplar
    in_catalog: true
    kin_score: 71.3
    mcp: &id005
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id006
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: common
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://github.com/flarum/framework/tree/main/framework/core/src/Mail
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
    mcp: &id007
      status: none
    slug: pusher
    status: profiled
    tags: &id008
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://github.com/flarum/framework/tree/main/extensions
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/community-forums/flarum/
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
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id003
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id004
  url: /providers/mailgun/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: exemplar
  in_catalog: true
  kin_score: 71.3
  mcp: *id005
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id006
  url: /providers/postmark/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id007
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id008
  url: /providers/pusher/
siblings:
- name: Circle
  rows: 36
  url: /applications/community-forums/circle/
- name: Discourse
  rows: 44
  url: /applications/community-forums/discourse/
- name: Lemmy
  rows: 2
  url: /applications/community-forums/lemmy/
- name: Mastodon
  rows: 10
  url: /applications/community-forums/mastodon/
- name: NodeBB
  rows: 9
  url: /applications/community-forums/nodebb/
sitemap: true
title: 'Flarum: Community & Forums reference app'
---
