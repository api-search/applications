---
app: Kimai
app_slug: kimai
app_url: https://github.com/kimai/kimai
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Authentik SAML
  - Azure AD (Entra ID) SAML
  - Google Workspace SAML
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: time-tracking
  name: Time Tracking & Timesheets
  url: /applications/time-tracking/
counts:
  declared: 3
  observed: 0
credits: []
evidence:
- route: dependency manifest
  url: https://raw.githubusercontent.com/kimai/kimai/main/composer.json
- route: documentation
  url: https://www.kimai.org/documentation/saml.html
- route: source code
  url: https://raw.githubusercontent.com/kimai/kimai/main/.env.dist
integrations:
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
    mcp: &id001
      status: none
    slug: authentik
    status: profiled
    tags: &id002
    - Authentication
    - Authorization
    - Identity Provider
    - LDAP
    url: /providers/authentik/
  layer: common
  name: Authentik SAML
  provider: authentik
  says: lists Authentik SAML as an integration
  source: https://www.kimai.org/documentation/saml.html
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
    mcp: &id003
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id004
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Azure AD (Entra ID) SAML
  provider: microsoft-entra
  says: lists Azure AD (Entra ID) SAML as an integration
  source: https://www.kimai.org/documentation/saml.html
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id005
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id006
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace SAML
  provider: google-workspace
  says: lists Google Workspace SAML as an integration
  source: https://www.kimai.org/documentation/saml.html
  tier: declared
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/time-tracking/kimai/
providers:
- agent_band: agent-ready
  agent_readiness: 37.2
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id001
  name: Authentik SAML
  slug: authentik
  status: profiled
  tags: *id002
  url: /providers/authentik/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id003
  name: Azure AD (Entra ID) SAML
  slug: microsoft-entra
  status: profiled
  tags: *id004
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id005
  name: Google Workspace SAML
  slug: google-workspace
  status: profiled
  tags: *id006
  url: /providers/google-workspace/
siblings:
- name: Clockify
  rows: 29
  url: /applications/time-tracking/clockify/
- name: Harvest
  rows: 28
  url: /applications/time-tracking/harvest/
- name: solidtime
  rows: 3
  url: /applications/time-tracking/solidtime/
- name: Super Productivity
  rows: 16
  url: /applications/time-tracking/super-productivity/
- name: Toggl Track
  rows: 24
  url: /applications/time-tracking/toggl-track/
sitemap: true
title: 'Kimai: Time Tracking & Timesheets reference app'
---
