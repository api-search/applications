---
app: Proton VPN
app_slug: proton-vpn
app_url: https://github.com/ProtonVPN/android-app
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Google Play Install Referrer
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
category:
  id: vpn-privacy
  name: VPN & Privacy Tools
  url: /applications/vpn-privacy/
counts:
  declared: 0
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/ch.protonvpn.android/latest/
- route: dependency manifest
  url: https://raw.githubusercontent.com/ProtonVPN/android-app/master/app/build.gradle
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
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
  name: Google Play Install Referrer
  provider: google-play
  says: ships the Google Play Install Referrer SDK or integration code
  source: https://raw.githubusercontent.com/ProtonVPN/android-app/master/app/build.gradle
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id003
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id004
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://raw.githubusercontent.com/ProtonVPN/android-app/master/app/build.gradle
  tier: observed
kind: open-source-saas
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/vpn-privacy/proton-vpn/
providers:
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 31.6
  mcp: *id001
  name: Google Play Install Referrer
  slug: google-play
  status: profiled
  tags: *id002
  url: /providers/google-play/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id003
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id004
  url: /providers/sentry-system/
siblings:
- name: Firezone
  rows: 3
  url: /applications/vpn-privacy/firezone/
- name: Headscale
  rows: 1
  url: /applications/vpn-privacy/headscale/
- name: Mullvad VPN
  rows: 1
  url: /applications/vpn-privacy/mullvad-vpn/
- name: NetBird
  rows: 18
  url: /applications/vpn-privacy/netbird/
- name: Tailscale
  rows: 23
  url: /applications/vpn-privacy/tailscale/
- name: WireGuard
  rows: 0
  url: /applications/vpn-privacy/wireguard/
sitemap: true
title: 'Proton VPN: VPN & Privacy Tools reference app'
---
