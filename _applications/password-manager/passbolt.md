---
app: Passbolt
app_slug: passbolt
app_url: https://github.com/passbolt/passbolt_api
author: API Evangelist
capabilities:
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
category:
  id: password-manager
  name: Password Manager
  url: /applications/password-manager/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/passbolt/passbolt_api/master/composer.json
- route: source code
  url: https://github.com/passbolt/passbolt_api/tree/master/plugins/PassboltCe/MultiFactorAuthentication/src/Utility
integrations:
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
    mcp: &id001
      status: none
    slug: duo-security
    status: profiled
    tags: &id002
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: domain
  name: Duo Security
  provider: duo-security
  says: ships the Duo Security SDK or integration code
  source: https://github.com/passbolt/passbolt_api/tree/master/plugins/PassboltCe/MultiFactorAuthentication/src/Utility
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
    mcp: &id003
      status: none
    slug: yubico
    status: profiled
    tags: &id004
    - Authentication
    - Company
    - Enterprise
    - Security
    url: /providers/yubico/
  layer: domain
  name: Yubico
  provider: yubico
  says: ships the Yubico SDK or integration code
  source: https://raw.githubusercontent.com/passbolt/passbolt_api/master/composer.json
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/password-manager/passbolt/
providers:
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id001
  name: Duo Security
  slug: duo-security
  status: profiled
  tags: *id002
  url: /providers/duo-security/
- agent_band: agent-aware
  agent_readiness: 25.0
  band: strong
  in_catalog: true
  kin_score: 58.0
  mcp: *id003
  name: Yubico
  slug: yubico
  status: profiled
  tags: *id004
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
- name: Psono
  rows: 14
  url: /applications/password-manager/psono/
- name: Vaultwarden
  rows: 6
  url: /applications/password-manager/vaultwarden/
sitemap: true
title: 'Passbolt: Password Manager reference app'
---
