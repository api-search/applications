---
app: 'mailcow: dockerized'
app_slug: mailcow-dockerized
app_url: https://github.com/mailcow/mailcow-dockerized
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-150.10.40
  key: AE-150.10.40
  layer: domain
  name: Email Security
  providers:
  - Spamhaus
  url: /capabilities/email/
  via_parent: Email
- attribution: Turbo EA
  id: BC-620.50.50
  key: BC-620.50.50
  layer: common
  name: Cryptography and Key Management
  providers:
  - Let's Encrypt
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
category:
  id: email-client
  name: Email Client & Hosting
  url: /applications/email-client/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: source code
  url: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/data/Dockerfiles/acme/acme.sh
- route: source code
  url: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/generate_config.sh
integrations:
- capability:
    attribution: Turbo EA
    id: BC-620.50.50
    key: BC-620.50.50
    name: Cryptography and Key Management
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 16.8
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id001
      status: none
    slug: lets-encrypt
    status: profiled
    tags: &id002
    - Certificates
    - Linux Foundation
    - Security
    - TLS
    url: /providers/lets-encrypt/
  layer: common
  name: Let's Encrypt
  provider: lets-encrypt
  says: ships the Let's Encrypt SDK or integration code
  source: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/data/Dockerfiles/acme/acme.sh
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.10.40
    key: AE-150.10.40
    name: Email Security
    url: /capabilities/email/
    via_parent: Email
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 21.5
    mcp: &id003
      status: none
    slug: spamhaus
    status: profiled
    tags: &id004
    - Anti-Spam
    - Company
    - Reputation
    - Security
    url: /providers/spamhaus/
  layer: domain
  name: Spamhaus
  provider: spamhaus
  says: ships the Spamhaus SDK or integration code
  source: https://raw.githubusercontent.com/mailcow/mailcow-dockerized/master/generate_config.sh
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/mailcow-dockerized/
providers:
- agent_band: agent-aware
  agent_readiness: 16.8
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id001
  name: Let's Encrypt
  slug: lets-encrypt
  status: profiled
  tags: *id002
  url: /providers/lets-encrypt/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 21.5
  mcp: *id003
  name: Spamhaus
  slug: spamhaus
  status: profiled
  tags: *id004
  url: /providers/spamhaus/
siblings:
- name: FairEmail
  rows: 26
  url: /applications/email-client/fairemail/
- name: Mail-in-a-Box
  rows: 5
  url: /applications/email-client/mail-in-a-box/
- name: Proton Mail (Android)
  rows: 3
  url: /applications/email-client/proton-mail-android/
- name: Roundcube Webmail
  rows: 11
  url: /applications/email-client/roundcube-webmail/
- name: Stalwart Mail Server
  rows: 19
  url: /applications/email-client/stalwart-mail-server/
- name: Thunderbird for Android
  rows: 7
  url: /applications/email-client/thunderbird-for-android/
sitemap: true
title: 'mailcow: dockerized: Email Client & Hosting reference app'
---
