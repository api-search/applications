---
app: Headscale
app_slug: headscale
app_url: https://github.com/juanfont/headscale
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-933
  key: AE-933
  layer: domain
  name: Mesh VPN & Remote Network Access
  providers:
  - Tailscale DERP relay map
  url: /capabilities/security-architecture-management/
  via_parent: Security Architecture Management
category:
  id: vpn-privacy
  name: VPN & Privacy Tools
  url: /applications/vpn-privacy/
counts:
  declared: 0
  observed: 1
credits: []
evidence:
- route: source code
  url: https://raw.githubusercontent.com/juanfont/headscale/main/config-example.yaml
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-933
    key: AE-933
    name: Mesh VPN & Remote Network Access
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.0
    band: developing
    in_catalog: true
    kin_score: 40.8
    mcp: &id001
      status: none
    slug: tailscale
    status: profiled
    tags: &id002
    - Mesh Networking
    - VPN
    - WireGuard
    - Zero Trust
    url: /providers/tailscale/
  layer: domain
  name: Tailscale DERP relay map
  provider: tailscale
  says: ships the Tailscale DERP relay map SDK or integration code
  source: https://raw.githubusercontent.com/juanfont/headscale/main/config-example.yaml
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/vpn-privacy/headscale/
providers:
- agent_band: agent-aware
  agent_readiness: 21.0
  band: developing
  in_catalog: true
  kin_score: 40.8
  mcp: *id001
  name: Tailscale DERP relay map
  slug: tailscale
  status: profiled
  tags: *id002
  url: /providers/tailscale/
siblings:
- name: Firezone
  rows: 3
  url: /applications/vpn-privacy/firezone/
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
title: 'Headscale: VPN & Privacy Tools reference app'
---
