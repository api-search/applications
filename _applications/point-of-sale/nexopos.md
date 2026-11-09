---
app: NexoPOS
app_slug: nexopos
app_url: https://github.com/Blair2004/NexoPOS
author: API Evangelist
capabilities:
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
  url: /capabilities/email/
  via_parent: Email
category:
  id: point-of-sale
  name: Point of Sale & In-Person Payments
  url: /applications/point-of-sale/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
- route: source code
  url: https://github.com/Blair2004/NexoPOS/blob/master/.env.example
integrations:
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
    mcp: &id001
      source: https://github.com/mailgun/mailgun-mcp-server
      status: verified
    slug: mailgun
    status: profiled
    tags: &id002
    - Email
    - Email Verification
    - SMTP
    - Transactional Email
    url: /providers/mailgun/
  layer: common
  name: Mailgun
  provider: mailgun
  says: ships the Mailgun SDK or integration code
  source: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
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
    mcp: &id003
      status: none
    slug: pusher
    status: profiled
    tags: &id004
    - Pub/Sub
    - Push Notifications
    - Real-Time
    - WebSocket
    url: /providers/pusher/
  layer: common
  name: Pusher
  provider: pusher
  says: ships the Pusher SDK or integration code
  source: https://github.com/Blair2004/NexoPOS/blob/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/point-of-sale/nexopos/
providers:
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 32.6
  mcp: *id001
  name: Mailgun
  slug: mailgun
  status: profiled
  tags: *id002
  url: /providers/mailgun/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: thin
  in_catalog: true
  kin_score: 38.6
  mcp: *id003
  name: Pusher
  slug: pusher
  status: profiled
  tags: *id004
  url: /providers/pusher/
siblings:
- name: Lightspeed Restaurant
  rows: 16
  url: /applications/point-of-sale/lightspeed-restaurant/
- name: Loyverse POS
  rows: 33
  url: /applications/point-of-sale/loyverse-pos/
- name: Odoo Point of Sale
  rows: 16
  url: /applications/point-of-sale/odoo-point-of-sale/
- name: Open Source Point of Sale
  rows: 3
  url: /applications/point-of-sale/open-source-point-of-sale/
- name: Square Point of Sale
  rows: 28
  url: /applications/point-of-sale/square-point-of-sale/
sitemap: true
title: 'NexoPOS: Point of Sale & In-Person Payments reference app'
---
