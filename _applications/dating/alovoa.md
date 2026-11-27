---
app: Alovoa
app_slug: alovoa
app_url: https://github.com/Alovoa/alovoa
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: dating
  name: Dating
  url: /applications/dating/
counts:
  declared: 0
  observed: 2
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/Alovoa/alovoa/blob/master/pom.xml
- route: source code
  url: https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
integrations:
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
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id001
      status: none
    slug: facebook
    status: profiled
    tags: &id002
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
  tier: observed
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
    mcp: &id003
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id004
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/Alovoa/alovoa/blob/master/src/main/resources/application.properties
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/dating/alovoa/
providers:
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id001
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id002
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id003
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id004
  url: /providers/google-identity-platform/
siblings:
- name: Bumble
  rows: 23
  url: /applications/dating/bumble/
- name: Duolicious
  rows: 9
  url: /applications/dating/duolicious/
- name: Grindr
  rows: 24
  url: /applications/dating/grindr/
- name: Hinge
  rows: 53
  url: /applications/dating/hinge/
- name: pH7Builder
  rows: 8
  url: /applications/dating/ph7builder/
- name: Tinder
  rows: 15
  url: /applications/dating/tinder/
sitemap: true
title: 'Alovoa: Dating reference app'
---
