---
app: NetBird
app_slug: netbird
app_url: https://github.com/netbirdio/netbird
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: domain
  name: End-User Computing Management
  providers:
  - FleetDM
  - Microsoft Intune
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Amazon Data Firehose
  - Datadog
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Authentik
  - Duo SSO
  - JumpCloud
  - Keycloak
  - Microsoft / Entra ID
  - Okta
  - Pocket ID
  - Zitadel
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - CrowdStrike Falcon
  - Huntress
  - SentinelOne Singularity / Data Lake
  - Wazuh
  url: /capabilities/threat-detection-response-management/
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
  declared: 18
  observed: 0
credits: []
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
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 72.1
    mcp: &id001
      status: none
    slug: amazon-kinesis-firehose
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Analytics
    - Data Delivery
    - Streaming
    url: /providers/amazon-kinesis-firehose/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.8
    band: exemplar
    in_catalog: true
    kin_score: 76.6
    mcp: &id003
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-s3
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Archives
    - Backup
    - Cloud Storage
    url: /providers/amazon-s3/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id005
      status: none
    slug: authentik
    status: profiled
    tags: &id006
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.4
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id007
      source: https://github.com/CrowdStrike/falcon-mcp
      status: verified
    slug: crowdstrike
    status: profiled
    tags: &id008
    - Cybersecurity
    - Endpoint Detection and Response
    - Endpoint Security
    - Threat Intelligence
    url: /providers/crowdstrike/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id009
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id010
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id011
      status: none
    slug: duo-security
    status: profiled
    tags: &id012
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 27.4
    band: strong
    in_catalog: true
    kin_score: 64.0
    mcp: &id013
      source: https://fleetdm.com/guides/fleet-mcp
      status: documented
    slug: fleet
    status: profiled
    tags: &id014
    - Company
    - Developer Tools
    - Device Management
    - MDM
    url: /providers/fleet/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id015
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id016
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 55.3
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id017
      status: none
    slug: huntress
    status: profiled
    tags: &id018
    - Company
    - Cybersecurity
    - Managed Detection and Response
    - Security
    url: /providers/huntress/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id019
      source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
      status: verified
    slug: jumpcloud
    status: profiled
    tags: &id020
    - Directory Services
    - Identity
    - MFA
    - SSO
    url: /providers/jumpcloud/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id021
      status: none
    slug: keycloak
    status: profiled
    tags: &id022
    - Authentication
    - Authorization
    - Identity and Access Management
    - OAuth
    url: /providers/keycloak/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id023
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id024
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 29.1
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id025
      status: none
    slug: microsoft-intune
    status: profiled
    tags: &id026
    - App Protection
    - Compliance
    - Device Configuration
    - Microsoft Azure
    url: /providers/microsoft-intune/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id027
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id028
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 16.9
    band: emerging
    in_catalog: true
    kin_score: 25.1
    mcp: &id029
      status: none
    slug: pocket-id
    status: profiled
    tags: &id030
    - Company
    - Identity
    - OAuth
    - OpenID Connect
    url: /providers/pocket-id/
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 22.0
    mcp: &id031
      source: https://github.com/Sentinel-One/purple-mcp
      status: verified
    slug: sentinelone
    status: profiled
    tags: &id032
    - Endpoint Detection and Response
    - Endpoint Security
    - Security
    - XDR
    url: /providers/sentinelone/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id033
      status: none
    slug: wazuh
    status: profiled
    tags: &id034
    - Company
    - Open Source
    - Security
    - XDR
    url: /providers/wazuh/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 54.1
    mcp: &id035
      status: none
    slug: zitadel
    status: profiled
    tags: &id036
    - Authentication
    - Authorization
    - Identity and Access Management
    - Open Source
    url: /providers/zitadel/
  layer: domain
  name: Zitadel
  provider: zitadel
  says: lists Zitadel as an integration
  source: https://docs.netbird.io/selfhosted/identity-providers
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/vpn-privacy/netbird/
providers:
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 72.1
  mcp: *id001
  name: Amazon Data Firehose
  slug: amazon-kinesis-firehose
  status: profiled
  tags: *id002
  url: /providers/amazon-kinesis-firehose/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: exemplar
  in_catalog: true
  kin_score: 76.6
  mcp: *id003
  name: Amazon S3
  slug: amazon-s3
  status: profiled
  tags: *id004
  url: /providers/amazon-s3/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id005
  name: Authentik
  slug: authentik
  status: profiled
  tags: *id006
  url: /providers/authentik/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id007
  name: CrowdStrike Falcon
  slug: crowdstrike
  status: profiled
  tags: *id008
  url: /providers/crowdstrike/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id009
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id010
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id011
  name: Duo SSO
  slug: duo-security
  status: profiled
  tags: *id012
  url: /providers/duo-security/
- agent_band: agent-aware
  agent_readiness: 27.4
  band: strong
  in_catalog: true
  kin_score: 64.0
  mcp: *id013
  name: FleetDM
  slug: fleet
  status: profiled
  tags: *id014
  url: /providers/fleet/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id015
  name: Google
  slug: google-identity-platform
  status: profiled
  tags: *id016
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id017
  name: Huntress
  slug: huntress
  status: profiled
  tags: *id018
  url: /providers/huntress/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id019
  name: JumpCloud
  slug: jumpcloud
  status: profiled
  tags: *id020
  url: /providers/jumpcloud/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id021
  name: Keycloak
  slug: keycloak
  status: profiled
  tags: *id022
  url: /providers/keycloak/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id023
  name: Microsoft / Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id024
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id025
  name: Microsoft Intune
  slug: microsoft-intune
  status: profiled
  tags: *id026
  url: /providers/microsoft-intune/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id027
  name: Okta
  slug: okta
  status: profiled
  tags: *id028
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 16.9
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id029
  name: Pocket ID
  slug: pocket-id
  status: profiled
  tags: *id030
  url: /providers/pocket-id/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 22.0
  mcp: *id031
  name: SentinelOne Singularity / Data Lake
  slug: sentinelone
  status: profiled
  tags: *id032
  url: /providers/sentinelone/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id033
  name: Wazuh
  slug: wazuh
  status: profiled
  tags: *id034
  url: /providers/wazuh/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 54.1
  mcp: *id035
  name: Zitadel
  slug: zitadel
  status: profiled
  tags: *id036
  url: /providers/zitadel/
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
title: 'NetBird: VPN & Privacy Tools reference app'
---
