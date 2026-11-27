---
app: Nuclei
app_slug: nuclei
app_url: https://github.com/projectdiscovery/nuclei
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-941
  key: AE-941
  layer: domain
  name: Internet Exposure Search & Attack-Surface Data
  providers:
  - BinaryEdge
  - Censys
  - Criminal IP
  - FOFA
  - GreyNoise
  - Hunter (Qi An Xin)
  - Netlas
  - ONYPHE
  - Quake (Qihoo 360)
  - Shodan
  - ZoomEye
  url: /capabilities/internet-exposure-search-attack-surface-data/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - Splunk
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Elasticsearch
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - Gitea
  - GitHub
  - GitLab
  - Jira
  - Linear
  url: /capabilities/software-product-engineering-management/
  via_parent: null
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 0
  observed: 18
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/projectdiscovery/nuclei/blob/dev/go.mod
- route: source code
  url: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
- route: source code
  url: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
- route: source code
  url: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 5.4
    mcp: &id001
      status: unknown
    slug: binaryedge
    status: profiled
    tags: &id002
    - Public APIs
    - Security
    url: /providers/binaryedge/
  layer: domain
  name: BinaryEdge
  provider: binaryedge
  says: ships the BinaryEdge SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.1
    band: strong
    in_catalog: true
    kin_score: 66.2
    mcp: &id003
      source: https://docs.censys.com/docs/platform-mcp-server
      status: verified
    slug: censys
    status: profiled
    tags: &id004
    - Attack Surface Management
    - Internet Intelligence
    - Security
    - Threat Hunting
    url: /providers/censys/
  layer: domain
  name: Censys
  provider: censys
  says: ships the Censys SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.0
    band: emerging
    in_catalog: true
    kin_score: 19.7
    mcp: &id005
      status: unchecked
    slug: criminal-ip
    status: profiled
    tags: &id006
    - Company
    - Cybersecurity
    - Data
    - Threat Intelligence
    url: /providers/criminal-ip/
  layer: domain
  name: Criminal IP
  provider: criminal-ip
  says: ships the Criminal IP SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
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
    agent_band: agent-aware
    agent_readiness: 28.5
    band: exemplar
    in_catalog: true
    kin_score: 78.4
    mcp: &id007
      source: https://www.elastic.co/docs/solutions/search/mcp
      status: verified
    slug: elastic
    status: profiled
    tags: &id008
    - Analytics
    - Observability
    - Search
    - Security
    url: /providers/elastic/
  layer: common
  name: Elasticsearch
  provider: elastic
  says: ships the Elasticsearch SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 4.0
    mcp: &id009
      status: unchecked
    slug: fofa
    status: profiled
    tags: &id010
    - Company
    - Cybersecurity
    - Search Engines
    - Threat Intelligence
    url: /providers/fofa/
  layer: domain
  name: FOFA
  provider: fofa
  says: ships the FOFA SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id011
      source: https://gitea.com/gitea/gitea-mcp
      status: verified
    slug: gitea
    status: profiled
    tags: &id012
    - CI/CD
    - DevOps
    - Gitea
    - Version Control
    url: /providers/gitea/
  layer: common
  name: Gitea
  provider: gitea
  says: ships the Gitea SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
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
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id015
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id016
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.6
    band: strong
    in_catalog: true
    kin_score: 61.8
    mcp: &id017
      source: https://github.com/GreyNoise-Intelligence/greynoise-mcp-server
      status: verified
    slug: greynoise
    status: profiled
    tags: &id018
    - Cybersecurity
    - IP Reputation
    - Security
    - Threat Intelligence
    url: /providers/greynoise/
  layer: domain
  name: GreyNoise
  provider: greynoise
  says: ships the GreyNoise SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id019
      status: unchecked
    slug: hunter-qianxin
    status: profiled
    tags: &id020
    - Company
    url: /providers/hunter-qianxin/
  layer: domain
  name: Hunter (Qi An Xin)
  provider: hunter-qianxin
  says: ships the Hunter (Qi An Xin) SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id021
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id022
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200
    key: software-product-engineering-management
    name: Software Product Engineering Management
    url: /capabilities/software-product-engineering-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.2
    band: developing
    in_catalog: true
    kin_score: 39.6
    mcp: &id023
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id024
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: common
  name: Linear
  provider: linear-app
  says: ships the Linear SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/trackers
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.3
    band: thin
    in_catalog: true
    kin_score: 36.3
    mcp: &id025
      status: unchecked
    slug: netlas
    status: profiled
    tags: &id026
    - Company
    - Internet Scanning
    - OSINT
    - Security
    url: /providers/netlas/
  layer: domain
  name: Netlas
  provider: netlas
  says: ships the Netlas SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.2
    band: developing
    in_catalog: true
    kin_score: 41.9
    mcp: &id027
      status: unchecked
    slug: onyphe
    status: profiled
    tags: &id028
    - Attack Surface Management
    - Internet Scanning
    - Passive DNS
    - Threat Intelligence
    url: /providers/onyphe/
  layer: domain
  name: ONYPHE
  provider: onyphe
  says: ships the ONYPHE SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.2
    mcp: &id029
      status: unchecked
    slug: quake-360
    status: profiled
    tags: &id030
    - Asset Mapping
    - Company
    - Cybersecurity
    - Security
    url: /providers/quake-360/
  layer: domain
  name: Quake (Qihoo 360)
  provider: quake-360
  says: ships the Quake (Qihoo 360) SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 22.4
    band: strong
    in_catalog: true
    kin_score: 61.6
    mcp: &id031
      status: unknown
    slug: shodan
    status: profiled
    tags: &id032
    - Devices
    - Internet
    - Search
    - Security
    url: /providers/shodan/
  layer: domain
  name: Shodan
  provider: shodan
  says: ships the Shodan SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
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
    agent_readiness: 54.4
    band: strong
    in_catalog: true
    kin_score: 63.1
    mcp: &id033
      status: none
    slug: splunk
    status: profiled
    tags: &id034
    - Analytics
    - Data Analysis
    - Logging
    - Machine Data
    url: /providers/splunk/
  layer: domain
  name: Splunk
  provider: splunk
  says: ships the Splunk SDK or integration code
  source: https://github.com/projectdiscovery/nuclei/tree/dev/pkg/reporting/exporters
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-941
    key: AE-941
    name: Internet Exposure Search & Attack-Surface Data
    url: /capabilities/internet-exposure-search-attack-surface-data/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.1
    band: thin
    in_catalog: true
    kin_score: 30.1
    mcp: &id035
      status: unchecked
    slug: zoomeye
    status: profiled
    tags: &id036
    - Asset Discovery
    - Company
    - Cybersecurity
    - Search Engines
    url: /providers/zoomeye/
  layer: domain
  name: ZoomEye
  provider: zoomeye
  says: ships the ZoomEye SDK or integration code
  source: https://github.com/projectdiscovery/uncover/tree/main/sources/agent
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/nuclei/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 5.4
  mcp: *id001
  name: BinaryEdge
  slug: binaryedge
  status: profiled
  tags: *id002
  url: /providers/binaryedge/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: strong
  in_catalog: true
  kin_score: 66.2
  mcp: *id003
  name: Censys
  slug: censys
  status: profiled
  tags: *id004
  url: /providers/censys/
- agent_band: agent-aware
  agent_readiness: 12.0
  band: emerging
  in_catalog: true
  kin_score: 19.7
  mcp: *id005
  name: Criminal IP
  slug: criminal-ip
  status: profiled
  tags: *id006
  url: /providers/criminal-ip/
- agent_band: agent-aware
  agent_readiness: 28.5
  band: exemplar
  in_catalog: true
  kin_score: 78.4
  mcp: *id007
  name: Elasticsearch
  slug: elastic
  status: profiled
  tags: *id008
  url: /providers/elastic/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 4.0
  mcp: *id009
  name: FOFA
  slug: fofa
  status: profiled
  tags: *id010
  url: /providers/fofa/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id011
  name: Gitea
  slug: gitea
  status: profiled
  tags: *id012
  url: /providers/gitea/
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
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id015
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id016
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 28.6
  band: strong
  in_catalog: true
  kin_score: 61.8
  mcp: *id017
  name: GreyNoise
  slug: greynoise
  status: profiled
  tags: *id018
  url: /providers/greynoise/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id019
  name: Hunter (Qi An Xin)
  slug: hunter-qianxin
  status: profiled
  tags: *id020
  url: /providers/hunter-qianxin/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id021
  name: Jira
  slug: jira
  status: profiled
  tags: *id022
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 35.2
  band: developing
  in_catalog: true
  kin_score: 39.6
  mcp: *id023
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id024
  url: /providers/linear-app/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: thin
  in_catalog: true
  kin_score: 36.3
  mcp: *id025
  name: Netlas
  slug: netlas
  status: profiled
  tags: *id026
  url: /providers/netlas/
- agent_band: agent-aware
  agent_readiness: 25.2
  band: developing
  in_catalog: true
  kin_score: 41.9
  mcp: *id027
  name: ONYPHE
  slug: onyphe
  status: profiled
  tags: *id028
  url: /providers/onyphe/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.2
  mcp: *id029
  name: Quake (Qihoo 360)
  slug: quake-360
  status: profiled
  tags: *id030
  url: /providers/quake-360/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: strong
  in_catalog: true
  kin_score: 61.6
  mcp: *id031
  name: Shodan
  slug: shodan
  status: profiled
  tags: *id032
  url: /providers/shodan/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: strong
  in_catalog: true
  kin_score: 63.1
  mcp: *id033
  name: Splunk
  slug: splunk
  status: profiled
  tags: *id034
  url: /providers/splunk/
- agent_band: agent-aware
  agent_readiness: 17.1
  band: thin
  in_catalog: true
  kin_score: 30.1
  mcp: *id035
  name: ZoomEye
  slug: zoomeye
  status: profiled
  tags: *id036
  url: /providers/zoomeye/
siblings:
- name: DefectDojo
  rows: 11
  url: /applications/security-scanning/defectdojo/
- name: OWASP Dependency-Track
  rows: 22
  url: /applications/security-scanning/owasp-dependency-track/
- name: Snyk
  rows: 27
  url: /applications/security-scanning/snyk/
- name: Tenable
  rows: 45
  url: /applications/security-scanning/tenable/
- name: Trivy
  rows: 4
  url: /applications/security-scanning/trivy/
- name: Wazuh
  rows: 17
  url: /applications/security-scanning/wazuh/
sitemap: true
title: 'Nuclei: Security Scanning & Vulnerability Management reference app'
---
