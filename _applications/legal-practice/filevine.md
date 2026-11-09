---
app: Filevine
app_slug: filevine
app_url: https://www.filevine.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: common
  name: Analytics & BI Management
  providers:
  - Domo
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.50
  key: AE-150.50
  layer: common
  name: Voice & Telephony
  providers:
  - Dialpad
  url: /capabilities/voice-telephony/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Workato
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: legal-practice
  name: Legal Practice Management
  url: /applications/legal-practice/
counts:
  declared: 5
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.filevine.com/integrations/
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-150.50
    key: AE-150.50
    name: Voice & Telephony
    url: /capabilities/voice-telephony/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 31.7
    mcp: &id001
      status: none
    slug: dialpad
    status: profiled
    tags: &id002
    - Artificial Intelligence
    - Communications
    - Contact Center
    - Voice
    url: /providers/dialpad/
  layer: common
  name: Dialpad
  provider: dialpad
  says: lists Dialpad as an integration
  source: https://www.filevine.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-610.50
    key: analytics-bi-management
    name: Analytics & BI Management
    url: /capabilities/analytics-bi-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 12.6
    mcp: &id003
      status: none
    slug: domo
    status: profiled
    tags: &id004
    - Analysis
    - Business Intelligence
    - Data
    - Pipelines
    url: /providers/domo/
  layer: common
  name: Domo
  provider: domo
  says: lists Domo as an integration
  source: https://www.filevine.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.6
    band: developing
    in_catalog: true
    kin_score: 44.1
    mcp: &id005
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id006
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.filevine.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.80
    key: AE-150.80
    name: Mailbox & Calendar Sync
    url: /capabilities/mailbox-calendar-sync/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 49.5
    band: exemplar
    in_catalog: true
    kin_score: 70.6
    mcp: &id007
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id008
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.filevine.com/integrations/
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-910
    key: AE-910
    name: Workflow Automation & iPaaS
    url: /capabilities/process-automation-governance/
    via_parent: Process Automation Governance
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.9
    band: exemplar
    in_catalog: true
    kin_score: 69.2
    mcp: &id009
      source: https://docs.workato.com/mcp.html
      status: verified
    slug: workato
    status: profiled
    tags: &id010
    - AI Agents
    - API Management
    - Automation
    - B2B
    url: /providers/workato/
  layer: common
  name: Workato
  provider: workato
  says: lists Workato as an integration
  source: https://www.filevine.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/legal-practice/filevine/
providers:
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 31.7
  mcp: *id001
  name: Dialpad
  slug: dialpad
  status: profiled
  tags: *id002
  url: /providers/dialpad/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 12.6
  mcp: *id003
  name: Domo
  slug: domo
  status: profiled
  tags: *id004
  url: /providers/domo/
- agent_band: agent-aware
  agent_readiness: 19.6
  band: developing
  in_catalog: true
  kin_score: 44.1
  mcp: *id005
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id006
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 49.5
  band: exemplar
  in_catalog: true
  kin_score: 70.6
  mcp: *id007
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id008
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id009
  name: Workato
  slug: workato
  status: profiled
  tags: *id010
  url: /providers/workato/
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
- name: Lawmatics
  rows: 29
  url: /applications/legal-practice/lawmatics/
- name: MyCase
  rows: 28
  url: /applications/legal-practice/mycase/
- name: PracticePanther
  rows: 19
  url: /applications/legal-practice/practicepanther/
- name: Smokeball
  rows: 4
  url: /applications/legal-practice/smokeball/
sitemap: true
title: 'Filevine: Legal Practice Management reference app'
---
