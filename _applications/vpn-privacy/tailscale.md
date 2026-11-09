---
app: Tailscale
app_slug: tailscale
app_url: https://tailscale.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: domain
  name: End-User Computing Management
  providers:
  - Iru (formerly Kandji)
  - Jamf Pro
  - Microsoft Intune
  - SimpleMDM
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: domain
  name: Observability Management
  providers:
  - Axiom
  - Cribl
  - Datadog
  - Elasticsearch / Logstash
  - Splunk (HEC)
  - Vector
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.20
  key: BC-600.50.20
  layer: domain
  name: Storage Management
  providers:
  - Amazon S3
  - Azure Blob Storage
  - Google Cloud Storage
  - Storj
  - Wasabi
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Microsoft Entra ID
  - Okta
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - DataSet by SentinelOne
  - Panther
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - GitHub sign-in
  - Google / Google Workspace sign-in
  - Sign in with Apple
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: vpn-privacy
  name: VPN & Privacy Tools
  url: /applications/vpn-privacy/
counts:
  declared: 23
  observed: 0
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
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
  facts:
    agent_band: agent-ready
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id003
      status: unchecked
    slug: axiom-co
    status: profiled
    tags: &id004
    - Event Data
    - Log Management
    - Logs
    - Observability
    url: /providers/axiom-co/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 40.9
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id005
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure-blob-storage
    status: profiled
    tags: &id006
    - Blobs
    - Cloud Storage
    - Microsoft
    - Microsoft Azure
    url: /providers/microsoft-azure-blob-storage/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 20.6
    band: developing
    in_catalog: true
    kin_score: 49.5
    mcp: &id007
      status: none
    slug: cribl
    status: profiled
    tags: &id008
    - Configuration
    - Data Lake
    - Data Pipeline
    - Data Routing
    url: /providers/cribl/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 49.6
    band: exemplar
    in_catalog: true
    kin_score: 79.2
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
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 22.4
    mcp: &id011
      source: https://github.com/Sentinel-One/purple-mcp
      status: verified
    slug: sentinelone
    status: profiled
    tags: &id012
    - Endpoint Detection and Response
    - Endpoint Security
    - Security
    - XDR
    url: /providers/sentinelone/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id013
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id014
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 63.4
    band: exemplar
    in_catalog: true
    kin_score: 85.4
    mcp: &id015
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: thin
    in_catalog: true
    kin_score: 36.8
    mcp: &id017
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id018
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 45.3
    band: exemplar
    in_catalog: true
    kin_score: 71.7
    mcp: &id019
      source: https://github.com/googleapis/gcloud-mcp
      status: verified
    slug: gcp-cloud-storage
    status: profiled
    tags: &id020
    - Archival
    - Backup
    - Blob Storage
    - Cloud Storage
    url: /providers/gcp-cloud-storage/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 37.2
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id021
      source: https://docs.iru.com/en/endpoint/integrations/ai-assistants/iru-mcp
      status: verified
    slug: kandji
    status: profiled
    tags: &id022
    - Company
    - Device Management
    - Mobile Device Management
    - apple-management
    url: /providers/kandji/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.8
    band: strong
    in_catalog: true
    kin_score: 62.2
    mcp: &id023
      status: none
    slug: jamf
    status: profiled
    tags: &id024
    - Apple Device Management
    - Company
    - Endpoint Security
    - MDM
    url: /providers/jamf/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id025
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id026
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.4
    band: exemplar
    in_catalog: true
    kin_score: 69.4
    mcp: &id027
      status: none
    slug: microsoft-intune
    status: profiled
    tags: &id028
    - App Protection
    - Compliance
    - Device Configuration
    - Microsoft Azure
    url: /providers/microsoft-intune/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id029
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id030
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 24.7
    band: thin
    in_catalog: true
    kin_score: 30.5
    mcp: &id031
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id032
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 34.5
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id033
      source: https://github.com/panther-labs/mcp-panther
      status: verified
    slug: panther
    status: profiled
    tags: &id034
    - Company
    - Detection and Response
    - SIEM
    - Security
    url: /providers/panther/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: strong
    in_catalog: true
    kin_score: 55.2
    mcp: &id035
      status: none
    slug: apple
    status: profiled
    tags: &id036
    - Apple
    - Developers
    - iOS
    - macOS
    url: /providers/apple/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 12.9
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id037
      status: none
    slug: simplemdm
    status: profiled
    tags: &id038
    - Apple
    - Enterprise
    - MDM
    - Mobile Device Management
    url: /providers/simplemdm/
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
  facts:
    agent_band: agent-ready
    agent_readiness: 53.5
    band: strong
    in_catalog: true
    kin_score: 61.4
    mcp: &id039
      status: none
    slug: splunk
    status: profiled
    tags: &id040
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
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
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 6.5
    mcp: &id041
      status: none
    slug: storj
    status: profiled
    tags: &id042
    - Cloud Storage
    - Object Storage
    - Public APIs
    - Storage
    url: /providers/storj/
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
  facts:
    agent_band: agent-aware
    agent_readiness: 25.5
    band: emerging
    in_catalog: true
    kin_score: 24.3
    mcp: &id043
      status: none
    slug: vector
    status: profiled
    tags: &id044
    - Data Pipeline
    - Logs
    - Metrics
    - Observability
    url: /providers/vector/
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
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 24.0
    mcp: &id045
      status: none
    slug: wasabi
    status: profiled
    tags: &id046
    - Cloud Storage
    - Object Storage
    - REST API
    - S3 Compatible
    url: /providers/wasabi/
  layer: domain
  name: Wasabi
  provider: wasabi
  says: lists Wasabi as an integration
  source: https://tailscale.com/kb/1255/log-streaming
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/vpn-privacy/tailscale/
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
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id003
  name: Axiom
  slug: axiom-co
  status: profiled
  tags: *id004
  url: /providers/axiom-co/
- agent_band: agent-ready
  agent_readiness: 40.9
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id005
  name: Azure Blob Storage
  slug: microsoft-azure-blob-storage
  status: profiled
  tags: *id006
  url: /providers/microsoft-azure-blob-storage/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: developing
  in_catalog: true
  kin_score: 49.5
  mcp: *id007
  name: Cribl
  slug: cribl
  status: profiled
  tags: *id008
  url: /providers/cribl/
- agent_band: agent-ready
  agent_readiness: 49.6
  band: exemplar
  in_catalog: true
  kin_score: 79.2
  mcp: *id009
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id010
  url: /providers/datadog/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 22.4
  mcp: *id011
  name: DataSet by SentinelOne
  slug: sentinelone
  status: profiled
  tags: *id012
  url: /providers/sentinelone/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id013
  name: Elasticsearch / Logstash
  slug: elastic
  status: profiled
  tags: *id014
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 63.4
  band: exemplar
  in_catalog: true
  kin_score: 85.4
  mcp: *id015
  name: GitHub sign-in
  slug: github
  status: profiled
  tags: *id016
  url: /providers/github/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: thin
  in_catalog: true
  kin_score: 36.8
  mcp: *id017
  name: Google / Google Workspace sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id018
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: exemplar
  in_catalog: true
  kin_score: 71.7
  mcp: *id019
  name: Google Cloud Storage
  slug: gcp-cloud-storage
  status: profiled
  tags: *id020
  url: /providers/gcp-cloud-storage/
- agent_band: agent-ready
  agent_readiness: 37.2
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id021
  name: Iru (formerly Kandji)
  slug: kandji
  status: profiled
  tags: *id022
  url: /providers/kandji/
- agent_band: agent-aware
  agent_readiness: 24.8
  band: strong
  in_catalog: true
  kin_score: 62.2
  mcp: *id023
  name: Jamf Pro
  slug: jamf
  status: profiled
  tags: *id024
  url: /providers/jamf/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id025
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id026
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 31.4
  band: exemplar
  in_catalog: true
  kin_score: 69.4
  mcp: *id027
  name: Microsoft Intune
  slug: microsoft-intune
  status: profiled
  tags: *id028
  url: /providers/microsoft-intune/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id029
  name: Okta
  slug: okta
  status: profiled
  tags: *id030
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: thin
  in_catalog: true
  kin_score: 30.5
  mcp: *id031
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id032
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id033
  name: Panther
  slug: panther
  status: profiled
  tags: *id034
  url: /providers/panther/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: strong
  in_catalog: true
  kin_score: 55.2
  mcp: *id035
  name: Sign in with Apple
  slug: apple
  status: profiled
  tags: *id036
  url: /providers/apple/
- agent_band: agent-aware
  agent_readiness: 12.9
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id037
  name: SimpleMDM
  slug: simplemdm
  status: profiled
  tags: *id038
  url: /providers/simplemdm/
- agent_band: agent-ready
  agent_readiness: 53.5
  band: strong
  in_catalog: true
  kin_score: 61.4
  mcp: *id039
  name: Splunk (HEC)
  slug: splunk
  status: profiled
  tags: *id040
  url: /providers/splunk/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 6.5
  mcp: *id041
  name: Storj
  slug: storj
  status: profiled
  tags: *id042
  url: /providers/storj/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: emerging
  in_catalog: true
  kin_score: 24.3
  mcp: *id043
  name: Vector
  slug: vector
  status: profiled
  tags: *id044
  url: /providers/vector/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 24.0
  mcp: *id045
  name: Wasabi
  slug: wasabi
  status: profiled
  tags: *id046
  url: /providers/wasabi/
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
- name: Proton VPN
  rows: 2
  url: /applications/vpn-privacy/proton-vpn/
- name: WireGuard
  rows: 0
  url: /applications/vpn-privacy/wireguard/
sitemap: true
title: 'Tailscale: VPN & Privacy Tools reference app'
---
