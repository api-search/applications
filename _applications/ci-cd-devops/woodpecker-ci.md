---
app: Woodpecker CI
app_slug: woodpecker-ci
app_url: https://github.com/woodpecker-ci/woodpecker
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4200.40
  key: software-construction-management
  layer: domain
  name: Software Construction Management
  providers:
  - Bitbucket Cloud + Data Center forges
  - GitHub forge (go-github)
  - GitLab forge (gitlab client-go)
  url: /capabilities/software-construction-management/
  via_parent: null
category:
  id: ci-cd-devops
  name: Code Hosting, CI/CD & DevOps
  url: /applications/ci-cd-devops/
counts:
  declared: 0
  observed: 3
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
- route: source code
  url: https://github.com/woodpecker-ci/woodpecker/tree/main/server/forge
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 71.9
    mcp: &id001
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: bitbucket
    status: profiled
    tags: &id002
    - Atlassian
    - CI/CD
    - Code Collaboration
    - Code Review
    url: /providers/bitbucket/
  layer: domain
  name: Bitbucket Cloud + Data Center forges
  provider: bitbucket
  says: ships the Bitbucket Cloud + Data Center forges SDK or integration code
  source: https://github.com/woodpecker-ci/woodpecker/tree/main/server/forge
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id003
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id004
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub forge (go-github)
  provider: github
  says: ships the GitHub forge (go-github) SDK or integration code
  source: https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4200.40
    key: software-construction-management
    name: Software Construction Management
    url: /capabilities/software-construction-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 54.5
    band: exemplar
    in_catalog: true
    kin_score: 86.3
    mcp: &id005
      source: https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/
      status: verified
    slug: gitlab
    status: profiled
    tags: &id006
    - Code
    - Developer Tools
    - Platform
    - Software Development
    url: /providers/gitlab/
  layer: domain
  name: GitLab forge (gitlab client-go)
  provider: gitlab
  says: ships the GitLab forge (gitlab client-go) SDK or integration code
  source: https://raw.githubusercontent.com/woodpecker-ci/woodpecker/main/go.mod
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/ci-cd-devops/woodpecker-ci/
providers:
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 71.9
  mcp: *id001
  name: Bitbucket Cloud + Data Center forges
  slug: bitbucket
  status: profiled
  tags: *id002
  url: /providers/bitbucket/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id003
  name: GitHub forge (go-github)
  slug: github
  status: profiled
  tags: *id004
  url: /providers/github/
- agent_band: agent-native
  agent_readiness: 54.5
  band: exemplar
  in_catalog: true
  kin_score: 86.3
  mcp: *id005
  name: GitLab forge (gitlab client-go)
  slug: gitlab
  status: profiled
  tags: *id006
  url: /providers/gitlab/
siblings:
- name: CircleCI
  rows: 54
  url: /applications/ci-cd-devops/circleci/
- name: Coolify
  rows: 21
  url: /applications/ci-cd-devops/coolify/
- name: Gitea
  rows: 24
  url: /applications/ci-cd-devops/gitea/
- name: GitHub
  rows: 6
  url: /applications/ci-cd-devops/github/
- name: GitLab
  rows: 54
  url: /applications/ci-cd-devops/gitlab/
sitemap: true
title: 'Woodpecker CI: Code Hosting, CI/CD & DevOps reference app'
---
