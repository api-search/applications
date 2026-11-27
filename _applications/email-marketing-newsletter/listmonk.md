---
app: listmonk
app_slug: listmonk
app_url: https://github.com/knadh/listmonk
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.20
  key: AE-150.10.20
  layer: domain
  name: Email Marketing Sends
  providers:
  - Amazon SES
  - Azure Communication Services
  - Forward Email (forwardemail.net)
  - Lettermint
  - Postmark
  - SendGrid
  - MailerSend
  - Resend
  url: /capabilities/email/
  via_parent: Email
- attribution: API Evangelist extension
  id: AE-160.70
  key: AE-160.70
  layer: common
  name: Bot Protection & CAPTCHA
  providers:
  - hCaptcha
  url: /capabilities/bot-protection-captcha/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Amazon Pinpoint (SMS)
  - Firebase Cloud Messaging
  - Novu
  url: /capabilities/push-notifications/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.10
  key: AE-150.20.10
  layer: common
  name: SMS
  providers:
  - Verimor (SMS, Turkey)
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
category:
  id: email-marketing-newsletter
  name: Email Marketing & Newsletters
  url: /applications/email-marketing-newsletter/
counts:
  declared: 6
  observed: 7
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/knadh/listmonk/master/go.mod
- route: documentation
  url: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
- route: source code
  url: https://github.com/knadh/listmonk/tree/master/internal/bounce/webhooks
- route: source code
  url: https://github.com/knadh/listmonk/tree/master/internal/media/providers
- route: source code
  url: https://raw.githubusercontent.com/knadh/listmonk/master/internal/captcha/captcha.go
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: exemplar
    in_catalog: true
    kin_score: 83.8
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
  layer: domain
  name: Amazon SES
  provider: amazon-ses
  says: ships the Amazon SES SDK or integration code
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/ses.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 41.9
    band: exemplar
    in_catalog: true
    kin_score: 73.7
    mcp: &id005
      status: none
    slug: microsoft-azure-communication-services
    status: profiled
    tags: &id006
    - CPaaS
    - Calling
    - Chat
    - Microsoft Azure
    url: /providers/microsoft-azure-communication-services/
  layer: domain
  name: Azure Communication Services
  provider: microsoft-azure-communication-services
  says: ships the Azure Communication Services SDK or integration code
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/azure.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.2
    band: strong
    in_catalog: true
    kin_score: 61.3
    mcp: &id009
      source: https://github.com/forwardemail/mcp-server
      status: verified
    slug: forward-email
    status: profiled
    tags: &id010
    - Email Forwarding
    - Email Hosting
    - Open Source
    - Secure Email
    url: /providers/forward-email/
  layer: domain
  name: Forward Email (forwardemail.net)
  provider: forward-email
  says: ships the Forward Email (forwardemail.net) SDK or integration code
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/forwardemail.go
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
    agent_readiness: 17.5
    band: thin
    in_catalog: true
    kin_score: 31.1
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
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/captcha/captcha.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.1
    band: developing
    in_catalog: true
    kin_score: 53.7
    mcp: &id013
      source: https://lettermint.co/docs/mcp
      status: verified
    slug: lettermint
    status: profiled
    tags: &id014
    - Company
    - Email
    - European
    - Transactional
    url: /providers/lettermint/
  layer: domain
  name: Lettermint
  provider: lettermint
  says: ships the Lettermint SDK or integration code
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/lettermint.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.5
    mcp: &id019
      source: https://github.com/ActiveCampaign/postmark-mcp
      status: verified
    slug: postmark
    status: profiled
    tags: &id020
    - Deliverability
    - Email
    - Messaging
    - Transactional Email
    url: /providers/postmark/
  layer: domain
  name: Postmark
  provider: postmark
  says: ships the Postmark SDK or integration code
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/postmark.go
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 40.7
    band: exemplar
    in_catalog: true
    kin_score: 84.0
    mcp: &id023
      status: none
    slug: sendgrid
    status: profiled
    tags: &id024
    - Email
    - Email API
    - Marketing Email
    - SMTP
    url: /providers/sendgrid/
  layer: domain
  name: SendGrid
  provider: sendgrid
  says: ships the SendGrid SDK or integration code
  source: https://raw.githubusercontent.com/knadh/listmonk/master/internal/bounce/webhooks/sendgrid.go
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
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-web-services
    status: profiled
    tags: &id002
    - Amazon
    - Amazon Web Services
    - Cloud
    - Networks
    url: /providers/amazon-web-services/
  layer: common
  name: Amazon Pinpoint (SMS)
  provider: amazon-pinpoint
  says: lists Amazon Pinpoint (SMS) as an integration
  source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id007
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id008
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase Cloud Messaging
  provider: firebase
  says: lists Firebase Cloud Messaging as an integration
  source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.5
    band: strong
    in_catalog: true
    kin_score: 57.5
    mcp: &id015
      source: https://developers.mailersend.com/mcp-server.html
      status: verified
    slug: mailersend
    status: profiled
    tags: &id016
    - Email
    - Marketing
    - SMTP
    - Transactional Email
    url: /providers/mailersend/
  layer: domain
  name: MailerSend
  provider: mailersend
  says: lists MailerSend as an integration
  source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.30
    key: AE-150.30
    name: Push Notifications
    url: /capabilities/push-notifications/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 61.2
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id017
      source: https://github.com/novuhq/novu-mcp-server
      status: verified
    slug: novu
    status: profiled
    tags: &id018
    - Email
    - In-App
    - Messaging
    - Notification
    url: /providers/novu/
  layer: common
  name: Novu
  provider: novu
  says: lists Novu as an integration
  source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.20
    key: AE-150.10.20
    name: Email Marketing Sends
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.8
    band: strong
    in_catalog: true
    kin_score: 56.8
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
  layer: domain
  name: Resend
  provider: resend
  says: lists Resend as an integration
  source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
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
    agent_band: agent-aware
    agent_readiness: 25.2
    band: minimal
    in_catalog: true
    kin_score: 8.9
    mcp: &id025
      status: none
    slug: verimor
    status: profiled
    tags: &id026
    - SMS
    - WhatsApp
    url: /providers/verimor/
  layer: common
  name: Verimor (SMS, Turkey)
  provider: verimor
  says: lists Verimor (SMS, Turkey) as an integration
  source: https://raw.githubusercontent.com/knadh/listmonk/master/docs/docs/content/messengers.md
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-marketing-newsletter/listmonk/
providers:
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id001
  name: Amazon Pinpoint (SMS)
  slug: amazon-web-services
  status: profiled
  tags: *id002
  url: /providers/amazon-web-services/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: exemplar
  in_catalog: true
  kin_score: 83.8
  mcp: *id003
  name: Amazon SES
  slug: amazon-ses
  status: profiled
  tags: *id004
  url: /providers/amazon-ses/
- agent_band: agent-ready
  agent_readiness: 41.9
  band: exemplar
  in_catalog: true
  kin_score: 73.7
  mcp: *id005
  name: Azure Communication Services
  slug: microsoft-azure-communication-services
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-communication-services/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id007
  name: Firebase Cloud Messaging
  slug: google-firebase
  status: profiled
  tags: *id008
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 38.2
  band: strong
  in_catalog: true
  kin_score: 61.3
  mcp: *id009
  name: Forward Email (forwardemail.net)
  slug: forward-email
  status: profiled
  tags: *id010
  url: /providers/forward-email/
- agent_band: agent-aware
  agent_readiness: 17.5
  band: thin
  in_catalog: true
  kin_score: 31.1
  mcp: *id011
  name: hCaptcha
  slug: hcaptcha
  status: profiled
  tags: *id012
  url: /providers/hcaptcha/
- agent_band: agent-aware
  agent_readiness: 24.1
  band: developing
  in_catalog: true
  kin_score: 53.7
  mcp: *id013
  name: Lettermint
  slug: lettermint
  status: profiled
  tags: *id014
  url: /providers/lettermint/
- agent_band: agent-ready
  agent_readiness: 56.5
  band: strong
  in_catalog: true
  kin_score: 57.5
  mcp: *id015
  name: MailerSend
  slug: mailersend
  status: profiled
  tags: *id016
  url: /providers/mailersend/
- agent_band: agent-ready
  agent_readiness: 61.2
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id017
  name: Novu
  slug: novu
  status: profiled
  tags: *id018
  url: /providers/novu/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.5
  mcp: *id019
  name: Postmark
  slug: postmark
  status: profiled
  tags: *id020
  url: /providers/postmark/
- agent_band: agent-ready
  agent_readiness: 49.8
  band: strong
  in_catalog: true
  kin_score: 56.8
  mcp: *id021
  name: Resend
  slug: resend
  status: profiled
  tags: *id022
  url: /providers/resend/
- agent_band: agent-ready
  agent_readiness: 40.7
  band: exemplar
  in_catalog: true
  kin_score: 84.0
  mcp: *id023
  name: SendGrid
  slug: sendgrid
  status: profiled
  tags: *id024
  url: /providers/sendgrid/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: minimal
  in_catalog: true
  kin_score: 8.9
  mcp: *id025
  name: Verimor (SMS, Turkey)
  slug: verimor
  status: profiled
  tags: *id026
  url: /providers/verimor/
siblings:
- name: beehiiv
  rows: 22
  url: /applications/email-marketing-newsletter/beehiiv/
- name: Ghost
  rows: 17
  url: /applications/email-marketing-newsletter/ghost/
- name: Keila
  rows: 7
  url: /applications/email-marketing-newsletter/keila/
- name: Klaviyo
  rows: 15
  url: /applications/email-marketing-newsletter/klaviyo/
- name: Mailchimp
  rows: 17
  url: /applications/email-marketing-newsletter/mailchimp/
- name: Mautic
  rows: 25
  url: /applications/email-marketing-newsletter/mautic/
- name: Substack
  rows: 4
  url: /applications/email-marketing-newsletter/substack/
sitemap: true
title: 'listmonk: Email Marketing & Newsletters reference app'
---
