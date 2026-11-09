---
app: Firezone
app_slug: firezone
app_url: https://github.com/firezone/firezone
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Google
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: vpn-privacy
  name: VPN & Privacy Tools
  url: /applications/vpn-privacy/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: documentation
  url: https://www.firezone.dev/kb/authenticate
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id001
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id002
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google
  provider: google-identity-platform
  says: lists Google as an integration
  source: https://www.firezone.dev/kb/authenticate
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id003
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id004
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: lists Microsoft Entra ID as an integration
  source: https://www.firezone.dev/kb/authenticate
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
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id005
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id006
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.firezone.dev/kb/authenticate
  tier: declared
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/vpn-privacy/firezone/
providers:
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id001
  name: Google
  slug: google-identity-platform
  status: profiled
  tags: *id002
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id003
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id004
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id005
  name: Okta
  slug: okta
  status: profiled
  tags: *id006
  url: /providers/okta/
siblings:
- name: Headscale
  rows: 1
  url: /applications/vpn-privacy/headscale/
- name: Mullvad VPN
  rows: 1
  url: /applications/vpn-privacy/mullvad-vpn/
- name: NetBird
  rows: 18
  url: /applications/vpn-privacy/netbird/
- name: Proton VPN
  rows: 2
  url: /applications/vpn-privacy/proton-vpn/
- name: Tailscale
  rows: 23
  url: /applications/vpn-privacy/tailscale/
- name: WireGuard
  rows: 0
  url: /applications/vpn-privacy/wireguard/
sitemap: true
title: 'Firezone: VPN & Privacy Tools reference app'
---
