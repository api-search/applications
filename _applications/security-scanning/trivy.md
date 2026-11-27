---
app: Trivy
app_slug: trivy
app_url: https://github.com/aquasecurity/trivy
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-250.10.20
  key: AE-250.10.20
  layer: domain
  name: Container Registries
  providers:
  - Amazon ECR
  - Azure Container Registry
  - Google Artifact Registry / GCR
  - GitHub Container Registry
  url: /capabilities/package-registries-distribution/
  via_parent: Package Registries & Distribution
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 1
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/aquasecurity/trivy/blob/main/go.mod
- route: source code
  url: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.5
    band: exemplar
    in_catalog: true
    kin_score: 75.2
    mcp: &id001
      source: https://github.com/awslabs/mcp
      status: verified
    slug: amazon-ecr
    status: profiled
    tags: &id002
    - Amazon Web Services
    - Container Images
    - Container Registry
    - Containers
    url: /providers/amazon-ecr/
  layer: domain
  name: Amazon ECR
  provider: amazon-ecr
  says: ships the Amazon ECR SDK or integration code
  source: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 28.8
    band: exemplar
    in_catalog: true
    kin_score: 68.5
    mcp: &id003
      source: https://learn.microsoft.com/en-us/azure/developer/azure-mcp-server/tools/azure-container-registry
      status: verified
    slug: azure-container-registry
    status: profiled
    tags: &id004
    - Container Images
    - Containers
    - Docker
    - Microsoft Azure
    url: /providers/azure-container-registry/
  layer: domain
  name: Azure Container Registry
  provider: azure-container-registry
  says: ships the Azure Container Registry SDK or integration code
  source: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.7
    band: strong
    in_catalog: true
    kin_score: 65.4
    mcp: &id007
      status: none
    slug: google-artifact-registry
    status: profiled
    tags: &id008
    - Artifacts
    - Containers
    - Google Cloud
    - Packages
    url: /providers/google-artifact-registry/
  layer: domain
  name: Google Artifact Registry / GCR
  provider: google-artifact-registry
  says: ships the Google Artifact Registry / GCR SDK or integration code
  source: https://github.com/aquasecurity/trivy/tree/main/pkg/fanal/image/registry
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-250.10.20
    key: AE-250.10.20
    name: Container Registries
    url: /capabilities/package-registries-distribution/
    via_parent: Package Registries & Distribution
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.7
    band: strong
    in_catalog: true
    kin_score: 61.8
    mcp: &id005
      source: https://github.com/github/github-mcp-server
      status: documented
    slug: github-container-registry
    status: profiled
    tags: &id006
    - Container Images
    - Containers
    - GitHub
    - Packages
    url: /providers/github-container-registry/
  layer: domain
  name: GitHub Container Registry
  provider: github-container-registry
  says: lists GitHub Container Registry as an integration
  source: https://github.com/aquasecurity/trivy-db
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/trivy/
providers:
- agent_band: agent-ready
  agent_readiness: 29.5
  band: exemplar
  in_catalog: true
  kin_score: 75.2
  mcp: *id001
  name: Amazon ECR
  slug: amazon-ecr
  status: profiled
  tags: *id002
  url: /providers/amazon-ecr/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: exemplar
  in_catalog: true
  kin_score: 68.5
  mcp: *id003
  name: Azure Container Registry
  slug: azure-container-registry
  status: profiled
  tags: *id004
  url: /providers/azure-container-registry/
- agent_band: agent-ready
  agent_readiness: 32.7
  band: strong
  in_catalog: true
  kin_score: 61.8
  mcp: *id005
  name: GitHub Container Registry
  slug: github-container-registry
  status: profiled
  tags: *id006
  url: /providers/github-container-registry/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: strong
  in_catalog: true
  kin_score: 65.4
  mcp: *id007
  name: Google Artifact Registry / GCR
  slug: google-artifact-registry
  status: profiled
  tags: *id008
  url: /providers/google-artifact-registry/
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
- name: Wazuh
  rows: 17
  url: /applications/security-scanning/wazuh/
sitemap: true
title: 'Trivy: Security Scanning & Vulnerability Management reference app'
---
