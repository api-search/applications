---
app: Wazuh
app_slug: wazuh
app_url: https://github.com/wazuh/wazuh
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: domain
  name: Threat Detection & Response Management
  providers:
  - Amazon CloudWatch Logs
  - Amazon GuardDuty
  - AWS CloudTrail
  - Google Cloud
  - Maltiverse
  - Microsoft Azure
  - Shuffle
  - VirusTotal
  - Amazon Security Lake
  - AWS Security Hub
  - Docker
  - GitHub
  - Microsoft Graph
  - Office 365
  url: /capabilities/threat-detection-response-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.40
  key: vulnerability-management
  layer: domain
  name: Vulnerability Management
  providers:
  - Amazon Inspector
  url: /capabilities/vulnerability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.30
  key: incident-response-management
  layer: common
  name: Incident Response Management
  providers:
  - PagerDuty
  url: /capabilities/incident-response-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 6
  observed: 11
credits: []
evidence:
- route: documentation
  url: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
- route: source code
  url: https://github.com/wazuh/wazuh/tree/main/wodles
- route: source code
  url: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 43.4
    band: exemplar
    in_catalog: true
    kin_score: 77.4
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudwatch
    status: profiled
    tags: &id002
    - Amazon Web Services
    - CloudWatch
    - Monitoring
    - Observability
    url: /providers/amazon-cloudwatch/
  layer: domain
  name: Amazon CloudWatch Logs
  provider: amazon-cloudwatch
  says: ships the Amazon CloudWatch Logs SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/services
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
    agent_band: agent-native
    agent_readiness: 42.2
    band: exemplar
    in_catalog: true
    kin_score: 73.8
    mcp: &id003
      source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
      status: documented
    slug: amazon-guardduty
    status: profiled
    tags: &id004
    - Amazon Web Services
    - Anomaly Detection
    - Compliance
    - Machine Learning
    url: /providers/amazon-guardduty/
  layer: domain
  name: Amazon GuardDuty
  provider: amazon-guardduty
  says: ships the Amazon GuardDuty SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/buckets_s3
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 71.1
    mcp: &id005
      status: none
    slug: amazon-inspector
    status: profiled
    tags: &id006
    - Amazon Web Services
    - Compliance
    - Container Security
    - EC2
    url: /providers/amazon-inspector/
  layer: domain
  name: Amazon Inspector
  provider: amazon-inspector
  says: ships the Amazon Inspector SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/services
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
    agent_readiness: 29.8
    band: exemplar
    in_catalog: true
    kin_score: 80.1
    mcp: &id009
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-cloudtrail
    status: profiled
    tags: &id010
    - Amazon Web Services
    - Audit
    - CloudTrail
    - Compliance
    url: /providers/amazon-cloudtrail/
  layer: domain
  name: AWS CloudTrail
  provider: amazon-cloudtrail
  says: ships the AWS CloudTrail SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/main/wodles/aws/buckets_s3
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
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 67.5
    mcp: &id017
      source: https://github.com/googleapis/mcp-toolbox
      status: verified
    slug: google-cloud-platform
    status: profiled
    tags: &id018
    - API Management
    - Cloud Computing
    - Infrastructure
    - Platform-as-a-Service
    url: /providers/google-cloud-platform/
  layer: domain
  name: Google Cloud
  provider: google-cloud-platform
  says: ships the Google Cloud SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/main/wodles/gcloud
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
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 6.2
    mcp: &id019
      status: unchecked
    slug: maltiverse
    status: profiled
    tags: &id020
    - Company
    - Cybersecurity
    - Threat Intelligence
    - threat-feed
    url: /providers/maltiverse/
  layer: domain
  name: Maltiverse
  provider: maltiverse
  says: ships the Maltiverse SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
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
    agent_readiness: 45.0
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id021
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-azure
    status: profiled
    tags: &id022
    - Cloud
    - Cloud Computing
    - Enterprise
    - Microsoft Azure
    url: /providers/microsoft-azure/
  layer: domain
  name: Microsoft Azure
  provider: microsoft-azure
  says: ships the Microsoft Azure SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/main/wodles/azure
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.30
    key: incident-response-management
    name: Incident Response Management
    url: /capabilities/incident-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id027
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id028
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: common
  name: PagerDuty
  provider: pagerduty
  says: ships the PagerDuty SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: developing
    in_catalog: true
    kin_score: 42.7
    mcp: &id029
      status: unknown
    slug: shuffle
    status: profiled
    tags: &id030
    - Automation
    - SOAR
    - Security
    - Workflows
    url: /providers/shuffle/
  layer: domain
  name: Shuffle
  provider: shuffle
  says: ships the Shuffle SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-150.40.10
    key: AE-150.40.10
    name: Team Chat Bridging
    url: /capabilities/in-app-chat/
    via_parent: In-App Chat
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id031
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id032
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
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
    agent_band: agent-aware
    agent_readiness: 26.1
    band: thin
    in_catalog: true
    kin_score: 39.0
    mcp: &id033
      source: https://github.com/VirusTotal/virustotal-mcp
      status: verified
    slug: virustotal
    status: profiled
    tags: &id034
    - Anti Malware
    - File Analysis
    - Security
    - Threat Intelligence
    url: /providers/virustotal/
  layer: domain
  name: VirusTotal
  provider: virustotal
  says: ships the VirusTotal SDK or integration code
  source: https://github.com/wazuh/wazuh/tree/v4.12.0/integrations
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
    agent_band: agent-aware
    agent_readiness: 25.9
    band: exemplar
    in_catalog: true
    kin_score: 74.6
    mcp: &id007
      source: https://docs.aws.amazon.com/agent-toolkit/latest/userguide/mcp-server.html
      status: documented
    slug: amazon-security-lake
    status: profiled
    tags: &id008
    - Amazon Web Services
    - Data Lake
    - SIEM
    - Security
    url: /providers/amazon-security-lake/
  layer: domain
  name: Amazon Security Lake
  provider: amazon-security-lake
  says: lists Amazon Security Lake as an integration
  source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
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
    agent_band: agent-native
    agent_readiness: 49.8
    band: exemplar
    in_catalog: true
    kin_score: 66.5
    mcp: &id011
      status: unknown
    slug: aws-security-hub
    status: profiled
    tags: &id012
    - Cloud Security Posture Management
    - Compliance
    - Findings
    - Security
    url: /providers/aws-security-hub/
  layer: domain
  name: AWS Security Hub
  provider: aws-security-hub
  says: lists AWS Security Hub as an integration
  source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
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
    agent_readiness: 32.4
    band: developing
    in_catalog: true
    kin_score: 51.7
    mcp: &id013
      source: https://github.com/docker/mcp-gateway
      status: verified
    slug: docker
    status: profiled
    tags: &id014
    - Cloud
    - Containers
    - DevOps
    - Developer Tools
    url: /providers/docker/
  layer: domain
  name: Docker
  provider: docker
  says: lists Docker as an integration
  source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
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
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
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
    agent_readiness: 39.0
    band: exemplar
    in_catalog: true
    kin_score: 69.7
    mcp: &id023
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-graph
    status: profiled
    tags: &id024
    - Azure AD
    - Collaboration
    - Contacts
    - Microsoft Graph
    url: /providers/microsoft-graph/
  layer: domain
  name: Microsoft Graph
  provider: microsoft-graph
  says: lists Microsoft Graph as an integration
  source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
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
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 70.1
    mcp: &id025
      source: https://learn.microsoft.com/en-us/microsoft-agent-365/tooling-servers-overview
      status: verified
    slug: microsoft-office-365
    status: profiled
    tags: &id026
    - Cloud
    - Collaboration
    - Enterprise
    - Microsoft
    url: /providers/microsoft-office-365/
  layer: domain
  name: Office 365
  provider: microsoft-office-365
  says: lists Office 365 as an integration
  source: https://github.com/wazuh/wazuh/tree/main/docs/ref/modules/integrations
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/wazuh/
providers:
- agent_band: agent-native
  agent_readiness: 43.4
  band: exemplar
  in_catalog: true
  kin_score: 77.4
  mcp: *id001
  name: Amazon CloudWatch Logs
  slug: amazon-cloudwatch
  status: profiled
  tags: *id002
  url: /providers/amazon-cloudwatch/
- agent_band: agent-native
  agent_readiness: 42.2
  band: exemplar
  in_catalog: true
  kin_score: 73.8
  mcp: *id003
  name: Amazon GuardDuty
  slug: amazon-guardduty
  status: profiled
  tags: *id004
  url: /providers/amazon-guardduty/
- agent_band: agent-native
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 71.1
  mcp: *id005
  name: Amazon Inspector
  slug: amazon-inspector
  status: profiled
  tags: *id006
  url: /providers/amazon-inspector/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: exemplar
  in_catalog: true
  kin_score: 74.6
  mcp: *id007
  name: Amazon Security Lake
  slug: amazon-security-lake
  status: profiled
  tags: *id008
  url: /providers/amazon-security-lake/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: exemplar
  in_catalog: true
  kin_score: 80.1
  mcp: *id009
  name: AWS CloudTrail
  slug: amazon-cloudtrail
  status: profiled
  tags: *id010
  url: /providers/amazon-cloudtrail/
- agent_band: agent-native
  agent_readiness: 49.8
  band: exemplar
  in_catalog: true
  kin_score: 66.5
  mcp: *id011
  name: AWS Security Hub
  slug: aws-security-hub
  status: profiled
  tags: *id012
  url: /providers/aws-security-hub/
- agent_band: agent-ready
  agent_readiness: 32.4
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id013
  name: Docker
  slug: docker
  status: profiled
  tags: *id014
  url: /providers/docker/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id015
  name: GitHub
  slug: github
  status: profiled
  tags: *id016
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 67.5
  mcp: *id017
  name: Google Cloud
  slug: google-cloud-platform
  status: profiled
  tags: *id018
  url: /providers/google-cloud-platform/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 6.2
  mcp: *id019
  name: Maltiverse
  slug: maltiverse
  status: profiled
  tags: *id020
  url: /providers/maltiverse/
- agent_band: agent-ready
  agent_readiness: 45.0
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id021
  name: Microsoft Azure
  slug: microsoft-azure
  status: profiled
  tags: *id022
  url: /providers/microsoft-azure/
- agent_band: agent-ready
  agent_readiness: 39.0
  band: exemplar
  in_catalog: true
  kin_score: 69.7
  mcp: *id023
  name: Microsoft Graph
  slug: microsoft-graph
  status: profiled
  tags: *id024
  url: /providers/microsoft-graph/
- agent_band: agent-ready
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 70.1
  mcp: *id025
  name: Office 365
  slug: microsoft-office-365
  status: profiled
  tags: *id026
  url: /providers/microsoft-office-365/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id027
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id028
  url: /providers/pagerduty/
- agent_band: agent-aware
  agent_readiness: 18.6
  band: developing
  in_catalog: true
  kin_score: 42.7
  mcp: *id029
  name: Shuffle
  slug: shuffle
  status: profiled
  tags: *id030
  url: /providers/shuffle/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id031
  name: Slack
  slug: slack
  status: profiled
  tags: *id032
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 26.1
  band: thin
  in_catalog: true
  kin_score: 39.0
  mcp: *id033
  name: VirusTotal
  slug: virustotal
  status: profiled
  tags: *id034
  url: /providers/virustotal/
siblings:
- name: DefectDojo
  rows: 11
  url: /applications/security-scanning/defectdojo/
- name: Nuclei
  rows: 18
  url: /applications/security-scanning/nuclei/
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
sitemap: true
title: 'Wazuh: Security Scanning & Vulnerability Management reference app'
---
