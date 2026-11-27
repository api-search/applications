---
app: DefectDojo
app_slug: defectdojo
app_url: https://github.com/DefectDojo/django-DefectDojo
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-620.40
  key: vulnerability-management
  layer: domain
  name: Vulnerability Management
  providers:
  - Black Duck
  - Bugcrowd
  - Cobalt (pentest)
  - Edgescan
  - SonarQube
  - Vulners
  url: /capabilities/vulnerability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4200
  key: software-product-engineering-management
  layer: common
  name: Software Product Engineering Management
  providers:
  - GitHub
  - GitLab
  - Jira
  url: /capabilities/software-product-engineering-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.40.10
  key: AE-150.40.10
  layer: common
  name: Team Chat Bridging
  providers:
  - Microsoft Teams
  - Slack
  url: /capabilities/in-app-chat/
  via_parent: In-App Chat
category:
  id: security-scanning
  name: Security Scanning & Vulnerability Management
  url: /applications/security-scanning/
counts:
  declared: 0
  observed: 11
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
- route: source code
  url: https://github.com/DefectDojo/django-DefectDojo/blob/master/dojo/notifications/models.py
- route: source code
  url: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
integrations:
- capability:
    attribution: Turbo EA
    id: BC-620.40
    key: vulnerability-management
    name: Vulnerability Management
    url: /capabilities/vulnerability-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 18.1
    band: developing
    in_catalog: true
    kin_score: 48.7
    mcp: &id001
      source: https://github.com/blackducksoftware/mcp-server
      status: verified
    slug: black-duck
    status: profiled
    tags: &id002
    - Application Security
    - Company
    - Enterprise
    - Software Composition Analysis
    url: /providers/black-duck/
  layer: domain
  name: Black Duck
  provider: black-duck
  says: ships the Black Duck SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
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
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 10.7
    mcp: &id003
      source: https://docs.bugcrowd.com/customers/ai-capabilities/ai-connect/
      status: documented
    slug: bugcrowd
    status: profiled
    tags: &id004
    - Cybersecurity
    - Public APIs
    - Security
    - Vulnerability Management
    url: /providers/bugcrowd/
  layer: domain
  name: Bugcrowd
  provider: bugcrowd
  says: ships the Bugcrowd SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 23.5
    mcp: &id005
      status: unknown
    slug: cobalt-io
    status: profiled
    tags: &id006
    - Company
    - Offensive Security
    - Penetration Testing
    - Security
    url: /providers/cobalt-io/
  layer: domain
  name: Cobalt (pentest)
  provider: cobalt-io
  says: ships the Cobalt (pentest) SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
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
    agent_band: agent-aware
    agent_readiness: 18.3
    band: emerging
    in_catalog: true
    kin_score: 15.8
    mcp: &id007
      status: unknown
    slug: edgescan
    status: profiled
    tags: &id008
    - API Testing
    - Company
    - Security
    - Vulnerability Management
    url: /providers/edgescan/
  layer: domain
  name: Edgescan
  provider: edgescan
  says: ships the Edgescan SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
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
    mcp: &id009
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id010
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: common
  name: GitHub
  provider: github
  says: ships the GitHub SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
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
    mcp: &id011
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id012
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: common
  name: GitLab
  provider: gitlab
  says: ships the GitLab SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
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
    mcp: &id013
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id014
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: ships the Jira SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id015
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id016
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: ships the Microsoft Teams SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/dojo/notifications/models.py
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
    mcp: &id017
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id018
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: ships the Slack SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
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
    agent_band: agent-ready
    agent_readiness: 35.0
    band: exemplar
    in_catalog: true
    kin_score: 72.4
    mcp: &id019
      source: https://github.com/SonarSource/sonarqube-mcp-server
      status: verified
    slug: sonarqube
    status: profiled
    tags: &id020
    - Code Quality
    - DevOps
    - Developer Tools
    - Security
    url: /providers/sonarqube/
  layer: domain
  name: SonarQube
  provider: sonarqube
  says: ships the SonarQube SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/tree/master/dojo/tools
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
    agent_band: agent-aware
    agent_readiness: 20.1
    band: developing
    in_catalog: true
    kin_score: 46.1
    mcp: &id021
      status: unchecked
    slug: vulners
    status: profiled
    tags: &id022
    - Intelligence
    - Platform
    - Security
    - Vulnerabilities
    url: /providers/vulners/
  layer: domain
  name: Vulners
  provider: vulners
  says: ships the Vulners SDK or integration code
  source: https://github.com/DefectDojo/django-DefectDojo/blob/master/requirements.txt
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/security-scanning/defectdojo/
providers:
- agent_band: agent-aware
  agent_readiness: 18.1
  band: developing
  in_catalog: true
  kin_score: 48.7
  mcp: *id001
  name: Black Duck
  slug: black-duck
  status: profiled
  tags: *id002
  url: /providers/black-duck/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 10.7
  mcp: *id003
  name: Bugcrowd
  slug: bugcrowd
  status: profiled
  tags: *id004
  url: /providers/bugcrowd/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.5
  mcp: *id005
  name: Cobalt (pentest)
  slug: cobalt-io
  status: profiled
  tags: *id006
  url: /providers/cobalt-io/
- agent_band: agent-aware
  agent_readiness: 18.3
  band: emerging
  in_catalog: true
  kin_score: 15.8
  mcp: *id007
  name: Edgescan
  slug: edgescan
  status: profiled
  tags: *id008
  url: /providers/edgescan/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id009
  name: GitHub
  slug: github
  status: profiled
  tags: *id010
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id011
  name: GitLab
  slug: gitlab
  status: profiled
  tags: *id012
  url: /providers/gitlab/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id013
  name: Jira
  slug: jira
  status: profiled
  tags: *id014
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id015
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id016
  url: /providers/microsoft-teams/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id017
  name: Slack
  slug: slack
  status: profiled
  tags: *id018
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 72.4
  mcp: *id019
  name: SonarQube
  slug: sonarqube
  status: profiled
  tags: *id020
  url: /providers/sonarqube/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: developing
  in_catalog: true
  kin_score: 46.1
  mcp: *id021
  name: Vulners
  slug: vulners
  status: profiled
  tags: *id022
  url: /providers/vulners/
siblings:
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
- name: Wazuh
  rows: 17
  url: /applications/security-scanning/wazuh/
sitemap: true
title: 'DefectDojo: Security Scanning & Vulnerability Management reference app'
---
