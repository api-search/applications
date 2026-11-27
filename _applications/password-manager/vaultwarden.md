---
app: Vaultwarden
app_slug: vaultwarden
app_url: https://github.com/dani-garcia/vaultwarden
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.60
  key: AE-160.60
  layer: domain
  name: Credential Security
  providers:
  - Have I Been Pwned
  url: /capabilities/credential-security/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.20
  key: AE-160.10.20
  layer: domain
  name: Multi-Factor Authentication
  providers:
  - Duo Security
  - Yubico
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: API Evangelist extension
  id: AE-230.40.30
  key: AE-230.40.30
  layer: domain
  name: Website Favicon & Logo Lookup
  providers:
  - DuckDuckGo
  - Google
  url: /capabilities/web-data/
  via_parent: Web Data
- attribution: API Evangelist extension
  id: AE-150.30
  key: AE-150.30
  layer: common
  name: Push Notifications
  providers:
  - Bitwarden
  url: /capabilities/push-notifications/
  via_parent: null
category:
  id: password-manager
  name: Password Manager
  url: /applications/password-manager/
counts:
  declared: 0
  observed: 6
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/Cargo.toml
- route: source code
  url: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
integrations:
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
    agent_readiness: 26.6
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id001
      source: https://github.com/bitwarden/mcp-server
      status: verified
    slug: bitwarden
    status: profiled
    tags: &id002
    - Open Source
    - Password Manager
    - Security
    - Vault
    url: /providers/bitwarden/
  layer: common
  name: Bitwarden
  provider: bitwarden
  says: ships the Bitwarden SDK or integration code
  source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.30
    key: AE-230.40.30
    name: Website Favicon & Logo Lookup
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.2
    band: developing
    in_catalog: true
    kin_score: 39.4
    mcp: &id003
      status: none
    slug: duckduckgo
    status: profiled
    tags: &id004
    - AI Chat
    - Browser
    - Privacy
    - Search
    url: /providers/duckduckgo/
  layer: domain
  name: DuckDuckGo
  provider: duckduckgo
  says: ships the DuckDuckGo SDK or integration code
  source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id005
      status: none
    slug: duo-security
    status: profiled
    tags: &id006
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: domain
  name: Duo Security
  provider: duo-security
  says: ships the Duo Security SDK or integration code
  source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-230.40.30
    key: AE-230.40.30
    name: Website Favicon & Logo Lookup
    url: /capabilities/web-data/
    via_parent: Web Data
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.8
    band: exemplar
    in_catalog: true
    kin_score: 68.9
    mcp: &id007
      source: https://github.com/google/mcp
      status: verified
    slug: google
    status: profiled
    tags: &id008
    - Advertising
    - Cloud
    - Developers
    - Google
    url: /providers/google/
  layer: domain
  name: Google
  provider: google
  says: ships the Google SDK or integration code
  source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.60
    key: AE-160.60
    name: Credential Security
    url: /capabilities/credential-security/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.8
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id009
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id010
    - Data Breaches
    - Identity
    - Pwned Passwords
    - Security
    url: /providers/have-i-been-pwned/
  layer: domain
  name: Have I Been Pwned
  provider: have-i-been-pwned
  says: ships the Have I Been Pwned SDK or integration code
  source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.20
    key: AE-160.10.20
    name: Multi-Factor Authentication
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.0
    band: strong
    in_catalog: true
    kin_score: 58.0
    mcp: &id011
      status: none
    slug: yubico
    status: profiled
    tags: &id012
    - Authentication
    - Company
    - Enterprise
    - Security
    url: /providers/yubico/
  layer: domain
  name: Yubico
  provider: yubico
  says: ships the Yubico SDK or integration code
  source: https://raw.githubusercontent.com/dani-garcia/vaultwarden/main/.env.template
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/password-manager/vaultwarden/
providers:
- agent_band: agent-aware
  agent_readiness: 26.6
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id001
  name: Bitwarden
  slug: bitwarden
  status: profiled
  tags: *id002
  url: /providers/bitwarden/
- agent_band: agent-aware
  agent_readiness: 20.2
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id003
  name: DuckDuckGo
  slug: duckduckgo
  status: profiled
  tags: *id004
  url: /providers/duckduckgo/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id005
  name: Duo Security
  slug: duo-security
  status: profiled
  tags: *id006
  url: /providers/duo-security/
- agent_band: agent-ready
  agent_readiness: 47.8
  band: exemplar
  in_catalog: true
  kin_score: 68.9
  mcp: *id007
  name: Google
  slug: google
  status: profiled
  tags: *id008
  url: /providers/google/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id009
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id010
  url: /providers/have-i-been-pwned/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id011
  name: Yubico
  slug: yubico
  status: profiled
  tags: *id012
  url: /providers/yubico/
siblings:
- name: 1Password
  rows: 18
  url: /applications/password-manager/1password/
- name: Bitwarden
  rows: 40
  url: /applications/password-manager/bitwarden/
- name: KeePassXC
  rows: 2
  url: /applications/password-manager/keepassxc/
- name: Passbolt
  rows: 2
  url: /applications/password-manager/passbolt/
- name: Psono
  rows: 14
  url: /applications/password-manager/psono/
sitemap: true
title: 'Vaultwarden: Password Manager reference app'
---
