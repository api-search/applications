---
app: 1Password
app_slug: 1password
app_url: https://1password.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4210.60
  key: configuration-secrets-management
  layer: domain
  name: Configuration & Secrets Management
  providers:
  - CircleCI
  - GitHub
  - Terraform
  url: /capabilities/configuration-secrets-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Duo Security
  - JumpCloud
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
  - Blumira
  - CrowdStrike
  - Datadog
  - Elastic
  - Microsoft Sentinel
  - Panther
  - Rapid7
  - Splunk
  - Sumo Logic
  url: /capabilities/threat-detection-response-management/
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
  id: password-manager
  name: Password Manager
  url: /applications/password-manager/
counts:
  declared: 17
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.onepassword.android/latest/
- route: documentation
  url: https://developer.1password.com/docs/ci-cd/
- route: documentation
  url: https://support.1password.com/events-reporting/
- route: documentation
  url: https://support.1password.com/sso/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.7
    mcp: &id029
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id030
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.onepassword.android/latest/
  tier: observed
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
    agent_readiness: 34.0
    band: strong
    in_catalog: true
    kin_score: 61.3
    mcp: &id001
      status: none
    slug: blumira
    status: profiled
    tags: &id002
    - Cloud
    - Company
    - Security
    - Software-as-a-Service
    url: /providers/blumira/
  layer: domain
  name: Blumira
  provider: blumira
  says: lists Blumira as an integration
  source: https://support.1password.com/events-reporting/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 73.5
    mcp: &id003
      source: https://github.com/CircleCI-Public/mcp-server-circleci
      status: verified
    slug: circleci
    status: profiled
    tags: &id004
    - CI/CD
    - Continuous Deployment
    - Continuous Integration
    - DevOps
    url: /providers/circleci/
  layer: domain
  name: CircleCI
  provider: circleci
  says: lists CircleCI as an integration
  source: https://developer.1password.com/docs/ci-cd/
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
    mcp: &id005
      source: https://github.com/CrowdStrike/falcon-mcp
      status: verified
    slug: crowdstrike
    status: profiled
    tags: &id006
    - Cybersecurity
    - Endpoint Detection and Response
    - Endpoint Security
    - Threat Intelligence
    url: /providers/crowdstrike/
  layer: domain
  name: CrowdStrike
  provider: crowdstrike
  says: lists CrowdStrike as an integration
  source: https://support.1password.com/events-reporting/
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id007
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id008
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://support.1password.com/events-reporting/
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
    mcp: &id009
      status: none
    slug: duo-security
    status: profiled
    tags: &id010
    - Authentication
    - Identity
    - MFA
    - Zero Trust
    url: /providers/duo-security/
  layer: domain
  name: Duo Security
  provider: duo-security
  says: lists Duo Security as an integration
  source: https://support.1password.com/sso/
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
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id011
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id012
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: domain
  name: Elastic
  provider: elastic
  says: lists Elastic as an integration
  source: https://support.1password.com/events-reporting/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id013
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id014
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://developer.1password.com/docs/ci-cd/
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
    mcp: &id015
      source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
      status: verified
    slug: jumpcloud
    status: profiled
    tags: &id016
    - Directory Services
    - Identity
    - MFA
    - SSO
    url: /providers/jumpcloud/
  layer: domain
  name: JumpCloud
  provider: jumpcloud
  says: lists JumpCloud as an integration
  source: https://support.1password.com/sso/
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
    mcp: &id017
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id018
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: lists Microsoft Entra ID as an integration
  source: https://support.1password.com/sso/
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
    agent_band: agent-aware
    agent_readiness: 27.2
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id019
      source: https://github.com/microsoft/sentinel-data-exploration-mcp
      status: verified
    slug: microsoft-sentinel
    status: profiled
    tags: &id020
    - Microsoft
    - SIEM
    - SOAR
    - Security
    url: /providers/microsoft-sentinel/
  layer: domain
  name: Microsoft Sentinel
  provider: microsoft-sentinel
  says: lists Microsoft Sentinel as an integration
  source: https://support.1password.com/events-reporting/
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
    mcp: &id021
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id022
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://support.1password.com/sso/
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
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id023
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id024
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: domain
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://support.1password.com/sso/
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
    agent_readiness: 34.8
    band: strong
    in_catalog: true
    kin_score: 56.9
    mcp: &id025
      source: https://github.com/panther-labs/mcp-panther
      status: verified
    slug: panther
    status: profiled
    tags: &id026
    - Company
    - Detection and Response
    - SIEM
    - Security
    url: /providers/panther/
  layer: domain
  name: Panther
  provider: panther
  says: lists Panther as an integration
  source: https://support.1password.com/events-reporting/
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
    agent_readiness: 28.8
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id027
      source: https://github.com/rapid7/rapid7-bulk-export-mcp
      status: verified
    slug: rapid7
    status: profiled
    tags: &id028
    - SIEM
    - Security
    - Vulnerability Management
    - XDR
    url: /providers/rapid7/
  layer: domain
  name: Rapid7
  provider: rapid7
  says: lists Rapid7 as an integration
  source: https://support.1password.com/events-reporting/
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
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id031
      status: none
    slug: splunk
    status: profiled
    tags: &id032
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://support.1password.com/events-reporting/
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
    agent_readiness: 48.2
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id033
      source: https://docs.sumologic.com/docs/search/mobot/
      status: documented
    slug: sumo-logic
    status: profiled
    tags: &id034
    - Logging
    - Monitoring
    - Observability
    - Security
    url: /providers/sumo-logic/
  layer: domain
  name: Sumo Logic
  provider: sumo-logic
  says: lists Sumo Logic as an integration
  source: https://support.1password.com/events-reporting/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4210.60
    key: configuration-secrets-management
    name: Configuration & Secrets Management
    url: /capabilities/configuration-secrets-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 42.5
    mcp: &id035
      source: https://github.com/hashicorp/terraform-mcp-server
      status: verified
    slug: terraform
    status: profiled
    tags: &id036
    - Cloud Infrastructure
    - DevOps
    - Infrastructure as Code
    - Open Source
    url: /providers/terraform/
  layer: domain
  name: Terraform
  provider: terraform
  says: lists Terraform as an integration
  source: https://developer.1password.com/docs/ci-cd/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/password-manager/1password/
providers:
- agent_band: agent-ready
  agent_readiness: 34.0
  band: strong
  in_catalog: true
  kin_score: 61.3
  mcp: *id001
  name: Blumira
  slug: blumira
  status: profiled
  tags: *id002
  url: /providers/blumira/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 73.5
  mcp: *id003
  name: CircleCI
  slug: circleci
  status: profiled
  tags: *id004
  url: /providers/circleci/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id005
  name: CrowdStrike
  slug: crowdstrike
  status: profiled
  tags: *id006
  url: /providers/crowdstrike/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id007
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id008
  url: /providers/datadog/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id009
  name: Duo Security
  slug: duo-security
  status: profiled
  tags: *id010
  url: /providers/duo-security/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id011
  name: Elastic
  slug: elastic
  status: profiled
  tags: *id012
  url: /providers/elastic/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id013
  name: GitHub
  slug: github
  status: profiled
  tags: *id014
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id015
  name: JumpCloud
  slug: jumpcloud
  status: profiled
  tags: *id016
  url: /providers/jumpcloud/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id017
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id018
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 27.2
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id019
  name: Microsoft Sentinel
  slug: microsoft-sentinel
  status: profiled
  tags: *id020
  url: /providers/microsoft-sentinel/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id021
  name: Okta
  slug: okta
  status: profiled
  tags: *id022
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id023
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id024
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 34.8
  band: strong
  in_catalog: true
  kin_score: 56.9
  mcp: *id025
  name: Panther
  slug: panther
  status: profiled
  tags: *id026
  url: /providers/panther/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id027
  name: Rapid7
  slug: rapid7
  status: profiled
  tags: *id028
  url: /providers/rapid7/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.7
  mcp: *id029
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id030
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id031
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id032
  url: /providers/splunk/
- agent_band: agent-ready
  agent_readiness: 48.2
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id033
  name: Sumo Logic
  slug: sumo-logic
  status: profiled
  tags: *id034
  url: /providers/sumo-logic/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 42.5
  mcp: *id035
  name: Terraform
  slug: terraform
  status: profiled
  tags: *id036
  url: /providers/terraform/
siblings:
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
- name: Vaultwarden
  rows: 6
  url: /applications/password-manager/vaultwarden/
sitemap: true
title: '1Password: Password Manager reference app'
---
