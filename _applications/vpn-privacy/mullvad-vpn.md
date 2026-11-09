---
app: Mullvad VPN
app_slug: mullvad-vpn
app_url: https://github.com/mullvad/mullvadvpn-app
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-904
  key: AE-904
  layer: common
  name: In-App Purchases & App Store Billing
  providers:
  - Google Play Billing
  url: /capabilities/in-app-purchases-app-store-billing/
  via_parent: null
category:
  id: vpn-privacy
  name: VPN & Privacy Tools
  url: /applications/vpn-privacy/
counts:
  declared: 0
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/net.mullvad.mullvadvpn/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/mullvad/mullvadvpn-app/main/android/gradle/libs.versions.toml
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 31.6
    mcp: &id001
      status: none
    slug: google-play
    status: profiled
    tags: &id002
    - Android
    - Application
    - Google Play
    - In-App Purchases
    url: /providers/google-play/
  layer: common
  name: Google Play Billing
  provider: google-play
  says: ships the Google Play Billing SDK or integration code
  source: https://raw.githubusercontent.com/mullvad/mullvadvpn-app/main/android/gradle/libs.versions.toml
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/vpn-privacy/mullvad-vpn/
providers:
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id001
  name: Google Play Billing
  slug: google-play
  status: profiled
  tags: *id002
  url: /providers/google-play/
siblings:
- name: Firezone
  rows: 3
  url: /applications/vpn-privacy/firezone/
- name: Headscale
  rows: 1
  url: /applications/vpn-privacy/headscale/
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
title: 'Mullvad VPN: VPN & Privacy Tools reference app'
---
