---
app: Smokeball
app_slug: smokeball
app_url: https://www.smokeball.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.30
  key: accounts-receivable-management
  layer: domain
  name: Accounts Receivable Management
  providers:
  - CollBox
  url: /capabilities/accounts-receivable-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50.30
  key: AE-150.50.30
  layer: domain
  name: Virtual Receptionists & Answering Services
  providers:
  - Answering Legal
  url: /capabilities/voice-telephony/
  via_parent: Voice & Telephony
- attribution: API Evangelist extension
  id: AE-140.60
  key: AE-140.60
  layer: common
  name: Reviews & Social Proof
  providers:
  - Birdeye
  url: /capabilities/reviews-social-proof/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - VXT
  url: /capabilities/voice-telephony/
  via_parent: null
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 4
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://marketplace.smokeball.com/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.50.30
    key: AE-150.50.30
    name: Virtual Receptionists & Answering Services
    url: /capabilities/voice-telephony/
    via_parent: Voice & Telephony
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id001
      status: unknown
    slug: answering-legal
    status: profiled
    tags: &id002
    - AI Chatbot
    - Call Answering
    - Legal Services
    - Virtual Receptionist
    url: /providers/answering-legal/
  layer: domain
  name: Answering Legal
  provider: answering-legal
  says: lists Answering Legal as an integration
  source: https://marketplace.smokeball.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.60
    key: AE-140.60
    name: Reviews & Social Proof
    url: /capabilities/reviews-social-proof/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 59.9
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id003
      source: https://docs.birdeye.com/mcp/introduction
      status: verified
    slug: birdeye
    status: profiled
    tags: &id004
    - Customer Experience
    - Reputation Management
    - Reviews
    - Surveys
    url: /providers/birdeye/
  layer: common
  name: Birdeye
  provider: birdeye
  says: lists Birdeye as an integration
  source: https://marketplace.smokeball.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.30
    key: accounts-receivable-management
    name: Accounts Receivable Management
    url: /capabilities/accounts-receivable-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.7
    mcp: &id005
      status: none
    slug: collbox
    status: profiled
    tags: &id006
    - Company
    - Finance
    - Law
    - Software-as-a-Service
    url: /providers/collbox/
  layer: domain
  name: CollBox
  provider: collbox
  says: lists CollBox as an integration
  source: https://marketplace.smokeball.com/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.8
    band: emerging
    in_catalog: true
    kin_score: 25.4
    mcp: &id007
      status: unknown
    slug: vxt
    status: profiled
    tags: &id008
    - Artificial Intelligence
    - Call Automation
    - Company
    - Legal Tech
    url: /providers/vxt/
  layer: common
  name: VXT
  provider: vxt
  says: lists VXT as an integration
  source: https://marketplace.smokeball.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/smokeball/
providers:
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id001
  name: Answering Legal
  slug: answering-legal
  status: profiled
  tags: *id002
  url: /providers/answering-legal/
- agent_band: agent-ready
  agent_readiness: 59.9
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id003
  name: Birdeye
  slug: birdeye
  status: profiled
  tags: *id004
  url: /providers/birdeye/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.7
  mcp: *id005
  name: CollBox
  slug: collbox
  status: profiled
  tags: *id006
  url: /providers/collbox/
- agent_band: human-only
  agent_readiness: 3.8
  band: emerging
  in_catalog: true
  kin_score: 25.4
  mcp: *id007
  name: VXT
  slug: vxt
  status: profiled
  tags: *id008
  url: /providers/vxt/
siblings:
- name: ArkCase
  rows: 8
  url: /applications/legal-practice/arkcase/
- name: Clio
  rows: 0
  url: /applications/legal-practice/clio/
- name: CosmoLex
  rows: 6
  url: /applications/legal-practice/cosmolex/
- name: Filevine
  rows: 5
  url: /applications/legal-practice/filevine/
- name: Lawmatics
  rows: 29
  url: /applications/legal-practice/lawmatics/
- name: MyCase
  rows: 28
  url: /applications/legal-practice/mycase/
- name: PracticePanther
  rows: 19
  url: /applications/legal-practice/practicepanther/
sitemap: true
title: 'Smokeball: Legal Practice Management reference app'
---
