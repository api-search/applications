---
access: understanding
agent_layer: []
apps:
- anchor: tailscale
  counts:
    declared: 23
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.tailscale.ipn/latest/
  - route: documentation
    url: https://tailscale.com/kb/1013/sso-providers
  - route: documentation
    url: https://tailscale.com/kb/1380/integrations-devices
  - route: integrations page
    url: https://tailscale.com/kb/1255/log-streaming
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Axiom
    provider: axiom-co
    says: lists Axiom as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Azure Blob Storage
    provider: microsoft-azure-blob-storage
    says: lists Azure Blob Storage as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Cribl
    provider: cribl
    says: lists Cribl as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: DataSet by SentinelOne
    provider: sentinelone
    says: lists DataSet by SentinelOne as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Elasticsearch / Logstash
    provider: elastic
    says: lists Elasticsearch / Logstash as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: GitHub sign-in
    provider: github
    says: lists GitHub sign-in as an integration
    source: https://tailscale.com/kb/1013/sso-providers
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google / Google Workspace sign-in
    provider: google-identity-platform
    says: lists Google / Google Workspace sign-in as an integration
    source: https://tailscale.com/kb/1013/sso-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Google Cloud Storage
    provider: gcp-cloud-storage
    says: lists Google Cloud Storage as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Iru (formerly Kandji)
    provider: kandji
    says: lists Iru (formerly Kandji) as an integration
    source: https://tailscale.com/kb/1380/integrations-devices
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Jamf Pro
    provider: jamf
    says: lists Jamf Pro as an integration
    source: https://tailscale.com/kb/1380/integrations-devices
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft Entra ID
    provider: microsoft-entra
    says: lists Microsoft Entra ID as an integration
    source: https://tailscale.com/kb/1013/sso-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft Intune
    provider: microsoft-intune
    says: lists Microsoft Intune as an integration
    source: https://tailscale.com/kb/1380/integrations-devices
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://tailscale.com/kb/1013/sso-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: OneLogin
    provider: onelogin
    says: lists OneLogin as an integration
    source: https://tailscale.com/kb/1013/sso-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Panther
    provider: panther
    says: lists Panther as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Sign in with Apple
    provider: apple
    says: lists Sign in with Apple as an integration
    source: https://tailscale.com/kb/1013/sso-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: SimpleMDM
    provider: simplemdm
    says: lists SimpleMDM as an integration
    source: https://tailscale.com/kb/1380/integrations-devices
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Splunk (HEC)
    provider: splunk
    says: lists Splunk (HEC) as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Storj
    provider: storj
    says: lists Storj as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Vector
    provider: vector
    says: lists Vector as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Wasabi
    provider: wasabi
    says: lists Wasabi as an integration
    source: https://tailscale.com/kb/1255/log-streaming
    tier: declared
  kind: commercial
  name: Tailscale
  page: /applications/vpn-privacy/tailscale/
  slug: tailscale
  url: https://tailscale.com/
- anchor: netbird
  counts:
    declared: 18
    observed: 0
  evidence:
  - route: documentation
    url: https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
  - route: documentation
    url: https://docs.netbird.io/manage/activity/event-streaming
  - route: documentation
    url: https://docs.netbird.io/selfhosted/identity-providers
  integrations:
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Amazon Data Firehose
    provider: amazon-kinesis-firehose
    says: lists Amazon Data Firehose as an integration
    source: https://docs.netbird.io/manage/activity/event-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Amazon S3
    provider: amazon-s3
    says: lists Amazon S3 as an integration
    source: https://docs.netbird.io/manage/activity/event-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Authentik
    provider: authentik
    says: lists Authentik as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: CrowdStrike Falcon
    provider: crowdstrike
    says: lists CrowdStrike Falcon as an integration
    source: https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    credit: null
    layer: domain
    name: Datadog
    provider: datadog
    says: lists Datadog as an integration
    source: https://docs.netbird.io/manage/activity/event-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Duo SSO
    provider: duo-security
    says: lists Duo SSO as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: FleetDM
    provider: fleet
    says: lists FleetDM as an integration
    source: https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
    tier: declared
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    credit: null
    layer: common
    name: Google
    provider: google-identity-platform
    says: lists Google as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Huntress
    provider: huntress
    says: lists Huntress as an integration
    source: https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: JumpCloud
    provider: jumpcloud
    says: lists JumpCloud as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Keycloak
    provider: keycloak
    says: lists Keycloak as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Microsoft / Entra ID
    provider: microsoft-entra
    says: lists Microsoft / Entra ID as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    credit: null
    layer: domain
    name: Microsoft Intune
    provider: microsoft-intune
    says: lists Microsoft Intune as an integration
    source: https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Pocket ID
    provider: pocket-id
    says: lists Pocket ID as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: SentinelOne Singularity / Data Lake
    provider: sentinelone
    says: lists SentinelOne Singularity / Data Lake as an integration
    source: https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    credit: null
    layer: domain
    name: Wazuh
    provider: wazuh
    says: lists Wazuh as an integration
    source: https://docs.netbird.io/manage/activity/event-streaming
    tier: declared
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    credit: null
    layer: domain
    name: Zitadel
    provider: zitadel
    says: lists Zitadel as an integration
    source: https://docs.netbird.io/selfhosted/identity-providers
    tier: declared
  kind: self-hosted
  name: NetBird
  page: /applications/vpn-privacy/netbird/
  slug: netbird
  url: https://github.com/netbirdio/netbird
- anchor: headscale
  counts:
    declared: 0
    observed: 1
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
    layer: domain
    name: Tailscale DERP relay map
    provider: tailscale
    says: ships the Tailscale DERP relay map SDK or integration code
    source: https://raw.githubusercontent.com/juanfont/headscale/main/config-example.yaml
    tier: observed
  kind: self-hosted
  name: Headscale
  page: /applications/vpn-privacy/headscale/
  slug: headscale
  url: https://github.com/juanfont/headscale
- anchor: firezone
  counts:
    declared: 3
    observed: 0
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
    layer: domain
    name: Okta
    provider: okta
    says: lists Okta as an integration
    source: https://www.firezone.dev/kb/authenticate
    tier: declared
  kind: open-source-saas
  name: Firezone
  page: /applications/vpn-privacy/firezone/
  slug: firezone
  url: https://github.com/firezone/firezone
- anchor: proton-vpn
  counts:
    declared: 0
    observed: 2
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
    layer: common
    name: Sentry
    provider: sentry-system
    says: ships the Sentry SDK or integration code
    source: https://raw.githubusercontent.com/ProtonVPN/android-app/master/app/build.gradle
    tier: observed
  kind: open-source-saas
  name: Proton VPN
  page: /applications/vpn-privacy/proton-vpn/
  slug: proton-vpn
  url: https://github.com/ProtonVPN/android-app
- anchor: mullvad-vpn
  counts:
    declared: 0
    observed: 1
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
    layer: common
    name: Google Play Billing
    provider: google-play
    says: ships the Google Play Billing SDK or integration code
    source: https://raw.githubusercontent.com/mullvad/mullvadvpn-app/main/android/gradle/libs.versions.toml
    tier: observed
  kind: open-source-saas
  name: Mullvad VPN
  page: /applications/vpn-privacy/mullvad-vpn/
  slug: mullvad-vpn
  url: https://github.com/mullvad/mullvadvpn-app
- anchor: wireguard
  counts:
    declared: 0
    observed: 0
  evidence:
  - route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
    url: https://reports.exodus-privacy.eu.org/en/reports/com.wireguard.android/latest/
  - route: dependency manifest
    url: https://raw.githubusercontent.com/WireGuard/wireguard-android/master/gradle/libs.versions.toml
  integrations: []
  kind: open-source-saas
  name: WireGuard
  page: /applications/vpn-privacy/wireguard/
  slug: wireguard
  url: https://www.wireguard.com/
author: API Evangelist
candidates: []
credits: []
html: public
id: vpn-privacy
layout: application
license: CC BY-NC-SA 4.0
marketplaces:
- category: Utilities
  store: apple-app-store
  url: https://developer.apple.com/app-store/categories/
- category: Tools
  store: google-play
  url: https://play.google.com/store/apps/category/TOOLS
- category: VPN
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#vpn
- category: Proxy
  store: awesome-selfhosted
  url: https://github.com/awesome-selfhosted/awesome-selfhosted#proxy
name: VPN & Privacy Tools
needs:
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  fit: exact
  layer: common
  why: consumer sign-in (Apple, Google, GitHub) is the default way into Tailscale, NetBird and Firezone
- capability:
    attribution: Turbo EA
    id: BC-4230.50
    key: tenant-identity-federation
    name: Tenant Identity Federation
    url: /capabilities/tenant-identity-federation/
    via_parent: null
  fit: exact
  layer: domain
  why: workforce IdPs (Entra, Okta, OneLogin, Zitadel, Keycloak, Authentik, Duo, JumpCloud) gate access to the mesh
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  fit: exact
  layer: domain
  why: network flow and audit logs stream to log/SIEM platforms; mobile clients ship crash reporting
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  fit: exact
  layer: domain
  why: SIEM/XDR destinations and EDR posture checks decide which devices may join
- capability:
    attribution: Turbo EA
    id: BC-600.50.20
    key: BC-600.50.20
    name: Storage Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: log archives land in S3 and S3-compatible stores
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  fit: exact
  layer: domain
  why: MDM deploys the client and feeds device posture
- capability:
    attribution: API Evangelist extension
    id: AE-933
    key: AE-933
    name: Mesh VPN & Remote Network Access
    url: /capabilities/security-architecture-management/
    via_parent: Security Architecture Management
  fit: exact
  layer: domain
  why: 'the domain itself: mesh VPN coordination and relays (DERP); nearest BC node, see Candidate extension nodes'
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  fit: exact
  layer: common
  why: Play install referrer in the Proton VPN Android build
- capability:
    attribution: API Evangelist extension
    id: AE-904
    key: AE-904
    name: In-App Purchases & App Store Billing
    url: /capabilities/in-app-purchases-app-store-billing/
    via_parent: null
  fit: exact
  layer: common
  why: subscriptions sold through Google Play Billing (Mullvad Android)
stack:
- capabilities:
  - capability:
      attribution: Turbo EA
      id: BC-4230.50
      key: tenant-identity-federation
      name: Tenant Identity Federation
      url: /capabilities/tenant-identity-federation/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 47.1
      apps:
      - Firezone
      - NetBird
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 81.8
      mcp:
        source: https://developer.okta.com/docs/concepts/mcp-server/
        status: verified
      name: Okta
      slug: okta
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      - https://tailscale.com/kb/1013/sso-providers
      - https://www.firezone.dev/kb/authenticate
      status: profiled
      tags:
      - Identity
      - Okta
      - SSO
      - Workforce Identity
      tier: declared
      url: /providers/okta/
    - agent_band: agent-ready
      agent_readiness: 28.7
      apps:
      - Firezone
      - NetBird
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 70.3
      mcp:
        status: none
      name: Microsoft Entra ID
      slug: microsoft-entra
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      - https://tailscale.com/kb/1013/sso-providers
      - https://www.firezone.dev/kb/authenticate
      status: profiled
      tags:
      - Authentication
      - Azure AD
      - Entra
      - Identity and Access Management
      tier: declared
      url: /providers/microsoft-entra/
    - agent_band: agent-ready
      agent_readiness: 37.2
      apps:
      - NetBird
      band: exemplar
      in_catalog: true
      kin_score: 73.1
      mcp:
        status: none
      name: Authentik
      slug: authentik
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity Provider
      - LDAP
      tier: declared
      url: /providers/authentik/
    - agent_band: agent-aware
      agent_readiness: 25.9
      apps:
      - NetBird
      band: developing
      in_catalog: true
      kin_score: 54.1
      mcp:
        status: none
      name: Zitadel
      slug: zitadel
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - Open Source
      tier: declared
      url: /providers/zitadel/
    - agent_band: agent-aware
      agent_readiness: 17.3
      apps:
      - NetBird
      band: thin
      in_catalog: true
      kin_score: 35.3
      mcp:
        status: none
      name: Keycloak
      slug: keycloak
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      status: profiled
      tags:
      - Authentication
      - Authorization
      - Identity and Access Management
      - OAuth
      tier: declared
      url: /providers/keycloak/
    - agent_band: agent-aware
      agent_readiness: 20.9
      apps:
      - NetBird
      band: thin
      in_catalog: true
      kin_score: 34.7
      mcp:
        status: none
      name: Duo SSO
      slug: duo-security
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      status: profiled
      tags:
      - Authentication
      - Identity
      - MFA
      - Zero Trust
      tier: declared
      url: /providers/duo-security/
    - agent_band: agent-ready
      agent_readiness: 31.3
      apps:
      - NetBird
      band: thin
      in_catalog: true
      kin_score: 33.6
      mcp:
        source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
        status: verified
      name: JumpCloud
      slug: jumpcloud
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      status: profiled
      tags:
      - Directory Services
      - Identity
      - MFA
      - SSO
      tier: declared
      url: /providers/jumpcloud/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Tailscale
      band: thin
      in_catalog: true
      kin_score: 29.5
      mcp:
        source: https://github.com/onelogin/onelogin-mcp
        status: verified
      name: OneLogin
      slug: onelogin
      sources:
      - https://tailscale.com/kb/1013/sso-providers
      status: profiled
      tags:
      - Identity
      - Identity and Access Management
      - Multi-Factor Authentication
      - SSO
      tier: declared
      url: /providers/onelogin/
    - agent_band: agent-aware
      agent_readiness: 16.9
      apps:
      - NetBird
      band: emerging
      in_catalog: true
      kin_score: 25.1
      mcp:
        status: none
      name: Pocket ID
      slug: pocket-id
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      status: profiled
      tags:
      - Company
      - Identity
      - OAuth
      - OpenID Connect
      tier: declared
      url: /providers/pocket-id/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 48.6
      apps:
      - NetBird
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 80.0
      mcp:
        source: https://github.com/datadog-labs/mcp-server
        status: verified
      name: Datadog
      slug: datadog
      sources:
      - https://docs.netbird.io/manage/activity/event-streaming
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Analytics
      - Dashboards
      - Datadog
      - Visualization
      tier: declared
      url: /providers/datadog/
    - agent_band: agent-aware
      agent_readiness: 28.5
      apps:
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 78.4
      mcp:
        source: https://www.elastic.co/docs/solutions/search/mcp
        status: verified
      name: Elasticsearch / Logstash
      slug: elastic
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Analytics
      - Observability
      - Search
      - Security
      tier: declared
      url: /providers/elastic/
    - agent_band: agent-ready
      agent_readiness: 35.3
      apps:
      - NetBird
      band: exemplar
      in_catalog: true
      kin_score: 72.1
      mcp:
        status: none
      name: Amazon Data Firehose
      slug: amazon-kinesis-firehose
      sources:
      - https://docs.netbird.io/manage/activity/event-streaming
      status: profiled
      tags:
      - Amazon Web Services
      - Analytics
      - Data Delivery
      - Streaming
      tier: declared
      url: /providers/amazon-kinesis-firehose/
    - agent_band: agent-ready
      agent_readiness: 54.4
      apps:
      - Tailscale
      band: strong
      in_catalog: true
      kin_score: 63.1
      mcp:
        status: none
      name: Splunk (HEC)
      slug: splunk
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Analytics
      - Data Analysis
      - Logging
      - Machine Data
      tier: declared
      url: /providers/splunk/
    - agent_band: agent-aware
      agent_readiness: 20.2
      apps:
      - Tailscale
      band: developing
      in_catalog: true
      kin_score: 51.6
      mcp:
        status: none
      name: Cribl
      slug: cribl
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Configuration
      - Data Lake
      - Data Pipeline
      - Data Routing
      tier: declared
      url: /providers/cribl/
    - agent_band: agent-ready
      agent_readiness: 45.7
      apps:
      - Tailscale
      band: thin
      in_catalog: true
      kin_score: 37.3
      mcp:
        source: https://github.com/axiomhq/mcp-server-axiom
        status: verified
      name: Axiom
      slug: axiom-co
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Event Data
      - Log Management
      - Logs
      - Observability
      tier: declared
      url: /providers/axiom-co/
    - agent_band: agent-aware
      agent_readiness: 24.9
      apps:
      - Tailscale
      band: emerging
      in_catalog: true
      kin_score: 23.1
      mcp:
        status: none
      name: Vector
      slug: vector
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Data Pipeline
      - Logs
      - Metrics
      - Observability
      tier: declared
      url: /providers/vector/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.50
      key: BC-600.50.50
      name: End-User Computing Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 29.1
      apps:
      - NetBird
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 68.1
      mcp:
        status: none
      name: Microsoft Intune
      slug: microsoft-intune
      sources:
      - https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
      - https://tailscale.com/kb/1380/integrations-devices
      status: profiled
      tags:
      - App Protection
      - Compliance
      - Device Configuration
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-intune/
    - agent_band: agent-ready
      agent_readiness: 36.9
      apps:
      - Tailscale
      band: strong
      in_catalog: true
      kin_score: 65.2
      mcp:
        source: https://docs.iru.com/en/endpoint/integrations/ai-assistants/iru-mcp
        status: verified
      name: Iru (formerly Kandji)
      slug: kandji
      sources:
      - https://tailscale.com/kb/1380/integrations-devices
      status: profiled
      tags:
      - Company
      - Device Management
      - Mobile Device Management
      - apple-management
      tier: declared
      url: /providers/kandji/
    - agent_band: agent-aware
      agent_readiness: 27.4
      apps:
      - NetBird
      band: strong
      in_catalog: true
      kin_score: 64.0
      mcp:
        source: https://fleetdm.com/guides/fleet-mcp
        status: documented
      name: FleetDM
      slug: fleet
      sources:
      - https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
      status: profiled
      tags:
      - Company
      - Developer Tools
      - Device Management
      - MDM
      tier: declared
      url: /providers/fleet/
    - agent_band: agent-aware
      agent_readiness: 24.3
      apps:
      - Tailscale
      band: strong
      in_catalog: true
      kin_score: 60.5
      mcp:
        status: none
      name: Jamf Pro
      slug: jamf
      sources:
      - https://tailscale.com/kb/1380/integrations-devices
      status: profiled
      tags:
      - Apple Device Management
      - Company
      - Endpoint Security
      - MDM
      tier: declared
      url: /providers/jamf/
    - agent_band: agent-aware
      agent_readiness: 12.7
      apps:
      - Tailscale
      band: developing
      in_catalog: true
      kin_score: 41.9
      mcp:
        status: none
      name: SimpleMDM
      slug: simplemdm
      sources:
      - https://tailscale.com/kb/1380/integrations-devices
      status: profiled
      tags:
      - Apple
      - Enterprise
      - MDM
      - Mobile Device Management
      tier: declared
      url: /providers/simplemdm/
  - capability:
      attribution: Turbo EA
      id: BC-600.50.20
      key: BC-600.50.20
      name: Storage Management
      url: /capabilities/it-infrastructure-management/
      via_parent: IT Infrastructure Management
    providers:
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - NetBird
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 76.6
      mcp:
        source: https://github.com/awslabs/mcp
        status: verified
      name: Amazon S3
      slug: amazon-s3
      sources:
      - https://docs.netbird.io/manage/activity/event-streaming
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Amazon Web Services
      - Archives
      - Backup
      - Cloud Storage
      tier: declared
      url: /providers/amazon-s3/
    - agent_band: agent-ready
      agent_readiness: 45.1
      apps:
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 74.1
      mcp:
        source: https://github.com/googleapis/gcloud-mcp
        status: verified
      name: Google Cloud Storage
      slug: gcp-cloud-storage
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Archival
      - Backup
      - Blob Storage
      - Cloud Storage
      tier: declared
      url: /providers/gcp-cloud-storage/
    - agent_band: agent-ready
      agent_readiness: 37.9
      apps:
      - Tailscale
      band: strong
      in_catalog: true
      kin_score: 66.3
      mcp:
        source: https://github.com/microsoft/mcp
        status: verified
      name: Azure Blob Storage
      slug: microsoft-azure-blob-storage
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Blobs
      - Cloud Storage
      - Microsoft
      - Microsoft Azure
      tier: declared
      url: /providers/microsoft-azure-blob-storage/
    - agent_band: human-only
      agent_readiness: 3.1
      apps:
      - Tailscale
      band: emerging
      in_catalog: true
      kin_score: 23.4
      mcp:
        status: none
      name: Wasabi
      slug: wasabi
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - REST API
      - S3 Compatible
      tier: declared
      url: /providers/wasabi/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - Tailscale
      band: minimal
      in_catalog: true
      kin_score: 5.7
      mcp:
        status: none
      name: Storj
      slug: storj
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Cloud Storage
      - Object Storage
      - Public APIs
      - Storage
      tier: declared
      url: /providers/storj/
  - capability:
      attribution: Turbo EA
      id: BC-620.30
      key: threat-detection-response-management
      name: Threat Detection & Response Management
      url: /capabilities/threat-detection-response-management/
      via_parent: null
    providers:
    - agent_band: human-only
      agent_readiness: 2.5
      apps:
      - NetBird
      - Tailscale
      band: emerging
      in_catalog: true
      kin_score: 22.0
      mcp:
        source: https://github.com/Sentinel-One/purple-mcp
        status: verified
      name: DataSet by SentinelOne
      slug: sentinelone
      sources:
      - https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Endpoint Detection and Response
      - Endpoint Security
      - Security
      - XDR
      tier: declared
      url: /providers/sentinelone/
    - agent_band: agent-ready
      agent_readiness: 34.4
      apps:
      - NetBird
      band: exemplar
      in_catalog: true
      kin_score: 67.2
      mcp:
        source: https://github.com/CrowdStrike/falcon-mcp
        status: verified
      name: CrowdStrike Falcon
      slug: crowdstrike
      sources:
      - https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
      status: profiled
      tags:
      - Cybersecurity
      - Endpoint Detection and Response
      - Endpoint Security
      - Threat Intelligence
      tier: declared
      url: /providers/crowdstrike/
    - agent_band: agent-ready
      agent_readiness: 55.3
      apps:
      - NetBird
      band: strong
      in_catalog: true
      kin_score: 63.5
      mcp:
        status: none
      name: Huntress
      slug: huntress
      sources:
      - https://docs.netbird.io/manage/access-control/endpoint-detection-and-response
      status: profiled
      tags:
      - Company
      - Cybersecurity
      - Managed Detection and Response
      - Security
      tier: declared
      url: /providers/huntress/
    - agent_band: agent-ready
      agent_readiness: 34.8
      apps:
      - Tailscale
      band: strong
      in_catalog: true
      kin_score: 56.9
      mcp:
        source: https://github.com/panther-labs/mcp-panther
        status: verified
      name: Panther
      slug: panther
      sources:
      - https://tailscale.com/kb/1255/log-streaming
      status: profiled
      tags:
      - Company
      - Detection and Response
      - SIEM
      - Security
      tier: declared
      url: /providers/panther/
    - agent_band: human-only
      agent_readiness: 0.0
      apps:
      - NetBird
      band: emerging
      in_catalog: true
      kin_score: 15.5
      mcp:
        status: none
      name: Wazuh
      slug: wazuh
      sources:
      - https://docs.netbird.io/manage/activity/event-streaming
      status: profiled
      tags:
      - Company
      - Open Source
      - Security
      - XDR
      tier: declared
      url: /providers/wazuh/
  - capability:
      attribution: API Evangelist extension
      id: AE-933
      key: AE-933
      name: Mesh VPN & Remote Network Access
      url: /capabilities/security-architecture-management/
      via_parent: Security Architecture Management
    providers:
    - agent_band: agent-aware
      agent_readiness: 21.0
      apps:
      - Headscale
      band: developing
      in_catalog: true
      kin_score: 40.8
      mcp:
        status: none
      name: Tailscale DERP relay map
      slug: tailscale
      sources:
      - https://raw.githubusercontent.com/juanfont/headscale/main/config-example.yaml
      status: profiled
      tags:
      - Mesh Networking
      - VPN
      - WireGuard
      - Zero Trust
      tier: observed
      url: /providers/tailscale/
  layer: domain
- capabilities:
  - capability:
      attribution: API Evangelist extension
      id: AE-160.10.30
      key: AE-160.10.30
      name: Social & Federated Login
      url: /capabilities/customer-sign-in/
      via_parent: Customer Sign-In
    providers:
    - agent_band: agent-ready
      agent_readiness: 33.7
      apps:
      - Firezone
      - NetBird
      - Tailscale
      band: strong
      in_catalog: true
      kin_score: 58.8
      mcp:
        status: none
      name: Google / Google Workspace sign-in
      slug: google-identity-platform
      sources:
      - https://docs.netbird.io/selfhosted/identity-providers
      - https://tailscale.com/kb/1013/sso-providers
      - https://www.firezone.dev/kb/authenticate
      status: profiled
      tags:
      - Authentication
      - Google Cloud
      - Identity
      - Multi-Tenancy
      tier: declared
      url: /providers/google-identity-platform/
    - agent_band: agent-ready
      agent_readiness: 62.4
      apps:
      - Tailscale
      band: exemplar
      in_catalog: true
      kin_score: 85.0
      mcp:
        source: https://github.com/github/github-mcp-server
        status: verified
      name: GitHub sign-in
      slug: github
      sources:
      - https://tailscale.com/kb/1013/sso-providers
      status: profiled
      tags:
      - Code
      - Developer Tools
      - Pipelines
      - Platform
      tier: declared
      url: /providers/github/
    - agent_band: agent-ready
      agent_readiness: 36.5
      apps:
      - Tailscale
      band: developing
      in_catalog: true
      kin_score: 52.9
      mcp:
        status: none
      name: Sign in with Apple
      slug: apple
      sources:
      - https://tailscale.com/kb/1013/sso-providers
      status: profiled
      tags:
      - Apple
      - Developers
      - iOS
      - macOS
      tier: declared
      url: /providers/apple/
  - capability:
      attribution: API Evangelist extension
      id: AE-904
      key: AE-904
      name: In-App Purchases & App Store Billing
      url: /capabilities/in-app-purchases-app-store-billing/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Mullvad VPN
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp: &id001
        status: none
      name: Google Play Billing
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/mullvad/mullvadvpn-app/main/android/gradle/libs.versions.toml
      status: profiled
      tags: &id002
      - Android
      - Application
      - Google Play
      - In-App Purchases
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: API Evangelist extension
      id: AE-902
      key: AE-902
      name: Mobile Attribution & Deep Linking
      url: /capabilities/mobile-attribution-deep-linking/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 38.7
      apps:
      - Proton VPN
      band: developing
      in_catalog: true
      kin_score: 51.3
      mcp: *id001
      name: Google Play Install Referrer
      slug: google-play
      sources:
      - https://raw.githubusercontent.com/ProtonVPN/android-app/master/app/build.gradle
      status: profiled
      tags: *id002
      tier: observed
      url: /providers/google-play/
  - capability:
      attribution: Turbo EA
      id: BC-4220.20
      key: observability-management
      name: Observability Management
      url: /capabilities/observability-management/
      via_parent: null
    providers:
    - agent_band: agent-ready
      agent_readiness: 50.2
      apps:
      - Proton VPN
      band: exemplar
      in_catalog: true
      kin_score: 80.7
      mcp:
        source: https://docs.sentry.io/product/sentry-mcp/
        status: verified
      name: Sentry
      slug: sentry-system
      sources:
      - https://raw.githubusercontent.com/ProtonVPN/android-app/master/app/build.gradle
      status: profiled
      tags:
      - APM
      - Application Monitoring
      - Bug Tracking
      - Developer Tools
      tier: observed
      url: /providers/sentry-system/
  layer: common
summary:
  coverage_pct: 100.0
  declared_only: 34
  distinct_providers: 37
  in_catalog: 37
  mcp:
    documented: 1
    none: 21
    unchecked: 0
    verified: 15
  mcp_verified: 15
  mean_kin_score: 53.6
  observed: 3
  queued: 0
  reference_apps: 7
title: 'VPN & Privacy Tools: application blueprint'
---
