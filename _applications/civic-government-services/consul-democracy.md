---
app: CONSUL Democracy
app_slug: consul-democracy
app_url: https://github.com/consuldemocracy/consuldemocracy
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-110.40.10
  key: AE-110.40.10
  layer: common
  name: Machine Translation
  providers:
  - Microsoft Translator (Bing)
  url: /capabilities/language-document-understanding/
  via_parent: Language & Document Understanding
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Airbrake
  url: /capabilities/observability-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook
  - Google sign-in
  - Twitter
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
category:
  id: civic-government-services
  name: Civic & Government Services
  url: /applications/civic-government-services/
counts:
  declared: 0
  observed: 5
credits: []
evidence:
- route: dependency manifest
  url: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 18.6
    band: emerging
    in_catalog: true
    kin_score: 25.8
    mcp: &id001
      status: none
    slug: airbrake
    status: profiled
    tags: &id002
    - Application Performance Monitoring
    - DevOps
    - Error Monitoring
    - Observability
    url: /providers/airbrake/
  layer: common
  name: Airbrake
  provider: airbrake
  says: ships the Airbrake SDK or integration code
  source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id003
      status: none
    slug: facebook
    status: profiled
    tags: &id004
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook
  provider: facebook
  says: ships the Facebook SDK or integration code
  source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    mcp: &id005
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id006
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: common
  name: Google sign-in
  provider: google-identity-platform
  says: ships the Google sign-in SDK or integration code
  source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-110.40.10
    key: AE-110.40.10
    name: Machine Translation
    url: /capabilities/language-document-understanding/
    via_parent: Language & Document Understanding
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id007
      status: unchecked
    slug: microsoft-translator
    status: queued for profiling
    tags: &id008 []
    url: null
  layer: common
  name: Microsoft Translator (Bing)
  provider: microsoft-translator
  says: ships the Microsoft Translator (Bing) SDK or integration code
  source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
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
    agent_band: agent-native
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 75.0
    mcp: &id009
      source: https://github.com/xdevplatform/xmcp
      status: verified
    slug: x
    status: profiled
    tags: &id010
    - Conversations
    - Social
    - Spaces
    - X
    url: /providers/x/
  layer: common
  name: Twitter
  provider: x
  says: ships the Twitter SDK or integration code
  source: https://github.com/consuldemocracy/consuldemocracy/blob/master/Gemfile
  tier: observed
kind: self-hosted
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/civic-government-services/consul-democracy/
providers:
- agent_band: agent-aware
  agent_readiness: 18.6
  band: emerging
  in_catalog: true
  kin_score: 25.8
  mcp: *id001
  name: Airbrake
  slug: airbrake
  status: profiled
  tags: *id002
  url: /providers/airbrake/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id003
  name: Facebook
  slug: facebook
  status: profiled
  tags: *id004
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id005
  name: Google sign-in
  slug: google-identity-platform
  status: profiled
  tags: *id006
  url: /providers/google-identity-platform/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id007
  name: Microsoft Translator (Bing)
  slug: microsoft-translator
  status: queued for profiling
  tags: *id008
  url: null
- agent_band: agent-native
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 75.0
  mcp: *id009
  name: Twitter
  slug: x
  status: profiled
  tags: *id010
  url: /providers/x/
siblings:
- name: Accela Civic Platform
  rows: 4
  url: /applications/civic-government-services/accela-civic-platform/
- name: Alaveteli
  rows: 4
  url: /applications/civic-government-services/alaveteli/
- name: Decidim
  rows: 7
  url: /applications/civic-government-services/decidim/
- name: FixMyStreet
  rows: 8
  url: /applications/civic-government-services/fixmystreet/
- name: Go Vocal (CitizenLab)
  rows: 10
  url: /applications/civic-government-services/go-vocal-citizenlab/
- name: Granicus (govDelivery)
  rows: 1
  url: /applications/civic-government-services/granicus-govdelivery/
- name: SeeClickFix (CivicPlus)
  rows: 21
  url: /applications/civic-government-services/seeclickfix-civicplus/
sitemap: true
title: 'CONSUL Democracy: Civic & Government Services reference app'
---
