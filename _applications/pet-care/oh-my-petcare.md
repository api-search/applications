---
app: oh-my-petcare
app_slug: oh-my-petcare
app_url: https://github.com/idonafraid-create/oh-my-petcare
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - Telegram
  - WeChat
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: pet-care
  name: Pet Care
  url: /applications/pet-care/
counts:
  declared: 2
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://github.com/idonafraid-create/oh-my-petcare
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: strong
    in_catalog: true
    kin_score: 58.4
    mcp: &id001
      status: none
    slug: telegram
    status: profiled
    tags: &id002
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: common
  name: Telegram
  provider: telegram
  says: lists Telegram as an integration
  source: https://github.com/idonafraid-create/oh-my-petcare
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.2
    band: developing
    in_catalog: true
    kin_score: 50.5
    mcp: &id003
      status: none
    slug: wechat
    status: profiled
    tags: &id004
    - Messaging
    - Mini Programs
    - Payments
    - Social
    url: /providers/wechat/
  layer: common
  name: WeChat
  provider: wechat
  says: lists WeChat as an integration
  source: https://github.com/idonafraid-create/oh-my-petcare
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/pet-care/oh-my-petcare/
providers:
- agent_band: agent-aware
  agent_readiness: 25.4
  band: strong
  in_catalog: true
  kin_score: 58.4
  mcp: *id001
  name: Telegram
  slug: telegram
  status: profiled
  tags: *id002
  url: /providers/telegram/
- agent_band: agent-aware
  agent_readiness: 24.2
  band: developing
  in_catalog: true
  kin_score: 50.5
  mcp: *id003
  name: WeChat
  slug: wechat
  status: profiled
  tags: *id004
  url: /providers/wechat/
siblings:
- name: Chewy
  rows: 4
  url: /applications/pet-care/chewy/
- name: Fi Smart Collar
  rows: 4
  url: /applications/pet-care/fi-smart-collar/
- name: PawSome AI
  rows: 2
  url: /applications/pet-care/pawsome-ai/
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
title: 'oh-my-petcare: Pet Care reference app'
---
