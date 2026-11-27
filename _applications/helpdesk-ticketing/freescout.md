---
app: FreeScout
app_slug: freescout
app_url: https://github.com/freescout-help-desk/freescout
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: domain
  name: SMS
  providers:
  - SMS Tickets Module (Twilio)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: domain
  name: Software Product Engineering Management
  providers:
  - Jira Integration Module
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: domain
  name: WhatsApp & OTT Messaging
  providers:
  - Facebook Integration Module
  - Telegram Integration Module
  - Twitter Integration Module
  - WhatsApp Integration Module
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - Extra Security Module (reCAPTCHA)
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack Integration Module
  - SMS notifications via MessageBird
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.20
  key: payment-processing-management
  layer: common
  name: Payment Processing Management
  providers:
  - WooCommerce Integration Module
  url: /capabilities/payment-processing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Social Login Module (Azure)
  - Social Login Module (Google)
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: helpdesk-ticketing
  name: Help Desk & Customer Support
  url: /applications/helpdesk-ticketing/
counts:
  declared: 12
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/freescout-help-desk/freescout/dist/composer.json
- route: integrations page
  url: https://freescout.net/modules/
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
    mcp: &id001
      status: none
    slug: google-recaptcha
    status: profiled
    tags: &id002
    - Abuse Prevention
    - Bot Detection
    - CAPTCHA
    - Fraud Prevention
    url: /providers/google-recaptcha/
  layer: common
  name: Extra Security Module (reCAPTCHA)
  provider: google-recaptcha
  says: lists Extra Security Module (reCAPTCHA) as an integration
  source: https://freescout.net/modules/
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id003
      status: none
    slug: facebook
    status: profiled
    tags: &id004
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: domain
  name: Facebook Integration Module
  provider: facebook
  says: lists Facebook Integration Module as an integration
  source: https://freescout.net/modules/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id005
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id006
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira Integration Module
  provider: jira
  says: lists Jira Integration Module as an integration
  source: https://freescout.net/modules/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id007
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id008
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack Integration Module
  provider: slack
  says: lists Slack Integration Module as an integration
  source: https://freescout.net/modules/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 70.3
    band: developing
    in_catalog: true
    kin_score: 50.0
    mcp: &id009
      source: https://github.com/messagebird/bird-ai
      status: verified
    slug: bird
    status: profiled
    tags: &id010
    - Communications
    - Email
    - SMS
    - WhatsApp
    url: /providers/bird/
  layer: common
  name: SMS notifications via MessageBird
  provider: bird
  says: lists SMS notifications via MessageBird as an integration
  source: https://freescout.net/modules/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.10
    key: AE-150.20.10
    name: SMS
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 56.6
    band: exemplar
    in_catalog: true
    kin_score: 90.8
    mcp: &id011
      source: https://www.twilio.com/docs/ai/mcp
      status: verified
    slug: twilio
    status: profiled
    tags: &id012
    - Authentication
    - Communications
    - Contact Center
    - Email
    url: /providers/twilio/
  layer: domain
  name: SMS Tickets Module (Twilio)
  provider: twilio
  says: lists SMS Tickets Module (Twilio) as an integration
  source: https://freescout.net/modules/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id013
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id014
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Social Login Module (Azure)
  provider: microsoft-entra
  says: lists Social Login Module (Azure) as an integration
  source: https://freescout.net/modules/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id015
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id016
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Social Login Module (Google)
  provider: google-identity-platform
  says: lists Social Login Module (Google) as an integration
  source: https://freescout.net/modules/
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
    agent_readiness: 25.3
    band: strong
    in_catalog: true
    kin_score: 56.8
    mcp: &id017
      status: none
    slug: telegram
    status: profiled
    tags: &id018
    - Bots
    - Chat
    - Messaging
    - Notification
    url: /providers/telegram/
  layer: domain
  name: Telegram Integration Module
  provider: telegram
  says: lists Telegram Integration Module as an integration
  source: https://freescout.net/modules/
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
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id019
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id020
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: domain
  name: Twitter Integration Module
  provider: x
  says: lists Twitter Integration Module as an integration
  source: https://freescout.net/modules/
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
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 72.3
    mcp: &id021
      status: none
    slug: whatsapp
    status: profiled
    tags: &id022
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: domain
  name: WhatsApp Integration Module
  provider: whatsapp
  says: lists WhatsApp Integration Module as an integration
  source: https://freescout.net/modules/
  tier: declared
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
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 54.6
    mcp: &id023
      source: https://developer.woocommerce.com/docs/features/mcp/
      status: verified
    slug: woocommerce
    status: profiled
    tags: &id024
    - E-Commerce
    - Open Source
    - Order
    - WooCommerce
    url: /providers/woocommerce/
  layer: common
  name: WooCommerce Integration Module
  provider: woocommerce
  says: lists WooCommerce Integration Module as an integration
  source: https://freescout.net/modules/
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/helpdesk-ticketing/freescout/
providers:
- agent_band: agent-ready
  agent_readiness: 34.9
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id001
  name: Extra Security Module (reCAPTCHA)
  slug: google-recaptcha
  status: profiled
  tags: *id002
  url: /providers/google-recaptcha/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id003
  name: Facebook Integration Module
  slug: facebook
  status: profiled
  tags: *id004
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id005
  name: Jira Integration Module
  slug: jira
  status: profiled
  tags: *id006
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id007
  name: Slack Integration Module
  slug: slack
  status: profiled
  tags: *id008
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 70.3
  band: developing
  in_catalog: true
  kin_score: 50.0
  mcp: *id009
  name: SMS notifications via MessageBird
  slug: bird
  status: profiled
  tags: *id010
  url: /providers/bird/
- agent_band: agent-native
  agent_readiness: 56.6
  band: exemplar
  in_catalog: true
  kin_score: 90.8
  mcp: *id011
  name: SMS Tickets Module (Twilio)
  slug: twilio
  status: profiled
  tags: *id012
  url: /providers/twilio/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id013
  name: Social Login Module (Azure)
  slug: microsoft-entra
  status: profiled
  tags: *id014
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id015
  name: Social Login Module (Google)
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: agent-aware
  agent_readiness: 25.3
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id017
  name: Telegram Integration Module
  slug: telegram
  status: profiled
  tags: *id018
  url: /providers/telegram/
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id019
  name: Twitter Integration Module
  slug: x
  status: profiled
  tags: *id020
  url: /providers/x/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 72.3
  mcp: *id021
  name: WhatsApp Integration Module
  slug: whatsapp
  status: profiled
  tags: *id022
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 54.6
  mcp: *id023
  name: WooCommerce Integration Module
  slug: woocommerce
  status: profiled
  tags: *id024
  url: /providers/woocommerce/
siblings:
- name: Chatwoot
  rows: 33
  url: /applications/helpdesk-ticketing/chatwoot/
- name: Freshdesk
  rows: 6
  url: /applications/helpdesk-ticketing/freshdesk/
- name: Help Scout
  rows: 24
  url: /applications/helpdesk-ticketing/help-scout/
- name: Intercom
  rows: 1
  url: /applications/helpdesk-ticketing/intercom/
- name: Zammad
  rows: 23
  url: /applications/helpdesk-ticketing/zammad/
- name: Zendesk
  rows: 2
  url: /applications/helpdesk-ticketing/zendesk/
sitemap: true
title: 'FreeScout: Help Desk & Customer Support reference app'
---
