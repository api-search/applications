---
app: Mail-in-a-Box
app_slug: mail-in-a-box
app_url: https://github.com/mail-in-a-box/mailinabox
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
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Nextcloud
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-3710.30
  key: asset-storage-tiering
  layer: common
  name: Asset Storage & Tiering
  providers:
  - Amazon S3
  - Backblaze B2
  url: /capabilities/asset-storage-tiering/
  via_parent: null
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
  observed: 5
credits: []
evidence:
- route: source code
  url: https://github.com/mail-in-a-box/mailinabox/tree/main/setup
- route: source code
  url: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
- route: source code
  url: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/status_checks.py
integrations:
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
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
  source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-3710.30
    key: asset-storage-tiering
    name: Asset Storage & Tiering
    url: /capabilities/asset-storage-tiering/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id003
      source: https://github.com/backblaze-labs/b2-mcp
      status: verified
    slug: backblaze
    status: profiled
    tags: &id004
    - Backup
    - Cloud Storage
    - Object Storage
    - Storage
    url: /providers/backblaze/
  layer: common
  name: Backblaze B2
  provider: backblaze
  says: ships the Backblaze B2 SDK or integration code
  source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/backup.py
  tier: observed
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
    agent_readiness: 17.2
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id005
      status: none
    slug: lets-encrypt
    status: profiled
    tags: &id006
    - Certificates
    - Linux Foundation
    - Security
    - TLS
    url: /providers/lets-encrypt/
  layer: common
  name: Let's Encrypt
  provider: lets-encrypt
  says: ships the Let's Encrypt SDK or integration code
  source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/ssl_certificates.py
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.0
    band: thin
    in_catalog: true
    kin_score: 33.0
    mcp: &id007
      status: none
    slug: nextcloud
    status: profiled
    tags: &id008
    - Collaboration
    - File Sharing
    - File Sync
    - Self-Hosted
    url: /providers/nextcloud/
  layer: domain
  name: Nextcloud
  provider: nextcloud
  says: ships the Nextcloud SDK or integration code
  source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/setup/nextcloud.sh
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
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 11.8
    mcp: &id009
      status: none
    slug: spamhaus
    status: profiled
    tags: &id010
    - Anti-Spam
    - Company
    - Reputation
    - Security
    url: /providers/spamhaus/
  layer: domain
  name: Spamhaus
  provider: spamhaus
  says: ships the Spamhaus SDK or integration code
  source: https://raw.githubusercontent.com/mail-in-a-box/mailinabox/main/management/status_checks.py
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/email-client/mail-in-a-box/
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
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id003
  name: Backblaze B2
  slug: backblaze
  status: profiled
  tags: *id004
  url: /providers/backblaze/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id005
  name: Let's Encrypt
  slug: lets-encrypt
  status: profiled
  tags: *id006
  url: /providers/lets-encrypt/
- agent_band: agent-aware
  agent_readiness: 19.0
  band: thin
  in_catalog: true
  kin_score: 33.0
  mcp: *id007
  name: Nextcloud
  slug: nextcloud
  status: profiled
  tags: *id008
  url: /providers/nextcloud/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 11.8
  mcp: *id009
  name: Spamhaus
  slug: spamhaus
  status: profiled
  tags: *id010
  url: /providers/spamhaus/
siblings:
- name: FairEmail
  rows: 26
  url: /applications/email-client/fairemail/
- name: 'mailcow: dockerized'
  rows: 2
  url: /applications/email-client/mailcow-dockerized/
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
title: 'Mail-in-a-Box: Email Client & Hosting reference app'
---
