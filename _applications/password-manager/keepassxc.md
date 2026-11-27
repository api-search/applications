---
app: KeePassXC
app_slug: keepassxc
app_url: https://github.com/keepassxreboot/keepassxc
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
  id: AE-230.40.30
  key: AE-230.40.30
  layer: domain
  name: Website Favicon & Logo Lookup
  providers:
  - DuckDuckGo
  url: /capabilities/web-data/
  via_parent: Web Data
category:
  id: password-manager
  name: Password Manager
  url: /applications/password-manager/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: source code
  url: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/core/Config.cpp
- route: source code
  url: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/gui/IconDownloader.cpp
- route: source code
  url: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/networking/HibpDownloader.cpp
integrations:
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
    mcp: &id001
      status: none
    slug: duckduckgo
    status: profiled
    tags: &id002
    - AI Chat
    - Browser
    - Privacy
    - Search
    url: /providers/duckduckgo/
  layer: domain
  name: DuckDuckGo
  provider: duckduckgo
  says: ships the DuckDuckGo SDK or integration code
  source: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/gui/IconDownloader.cpp
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
    mcp: &id003
      status: none
    slug: have-i-been-pwned
    status: profiled
    tags: &id004
    - Data Breaches
    - Identity
    - Pwned Passwords
    - Security
    url: /providers/have-i-been-pwned/
  layer: domain
  name: Have I Been Pwned
  provider: have-i-been-pwned
  says: ships the Have I Been Pwned SDK or integration code
  source: https://raw.githubusercontent.com/keepassxreboot/keepassxc/develop/src/networking/HibpDownloader.cpp
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/password-manager/keepassxc/
providers:
- agent_band: agent-aware
  agent_readiness: 20.2
  band: developing
  in_catalog: true
  kin_score: 39.4
  mcp: *id001
  name: DuckDuckGo
  slug: duckduckgo
  status: profiled
  tags: *id002
  url: /providers/duckduckgo/
- agent_band: agent-ready
  agent_readiness: 31.8
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id003
  name: Have I Been Pwned
  slug: have-i-been-pwned
  status: profiled
  tags: *id004
  url: /providers/have-i-been-pwned/
siblings:
- name: 1Password
  rows: 18
  url: /applications/password-manager/1password/
- name: Bitwarden
  rows: 40
  url: /applications/password-manager/bitwarden/
- name: Passbolt
  rows: 2
  url: /applications/password-manager/passbolt/
- name: Psono
  rows: 14
  url: /applications/password-manager/psono/
- name: Vaultwarden
  rows: 6
  url: /applications/password-manager/vaultwarden/
sitemap: true
title: 'KeePassXC: Password Manager reference app'
---
