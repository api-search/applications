---
app: Box
app_slug: box
app_url: https://www.box.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620
  key: cybersecurity-management
  layer: common
  name: Cybersecurity Management
  providers:
  - Broadcom
  - Palo Alto Networks
  - Splunk
  url: /capabilities/cybersecurity-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-170.80
  key: AE-170.80
  layer: common
  name: Design & Creative Editing
  providers:
  - Adobe Express
  url: /capabilities/design-creative-editing/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.50.50
  key: BC-600.50.50
  layer: common
  name: End-User Computing Management
  providers:
  - Google
  - Microsoft 365 (Copilot)
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-4210.50
  key: feature-flag-management
  layer: common
  name: Feature Flag Management
  providers:
  - Split
  url: /capabilities/feature-flag-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Oracle NetSuite
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: common
  name: Human Capital Management
  providers:
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Okta
  url: /capabilities/identity-access-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Amplitude
  - Firebase (Crashlytics / Analytics)
  - Pendo
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - Anthropic (Claude)
  - Google Gemini
  - OpenAI (ChatGPT)
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: cloud-storage-file-sync
  name: Cloud Storage & File Sync
  url: /applications/cloud-storage-file-sync/
counts:
  declared: 14
  observed: 4
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
- route: integrations page
  url: https://www.box.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 56.9
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id003
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id004
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id009
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id010
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: strong
    in_catalog: true
    kin_score: 57.0
    mcp: &id025
      source: https://support.pendo.io/hc/en-us/articles/41102236924955
      status: verified
    slug: pendoio
    status: profiled
    tags: &id026
    - Company
    - Digital Adoption
    - Product Analytics
    - Product Experience
    url: /providers/pendoio/
  layer: common
  name: Pendo
  provider: pendoio
  says: ships the Pendo SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4210.50
    key: feature-flag-management
    name: Feature Flag Management
    url: /capabilities/feature-flag-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: thin
    in_catalog: true
    kin_score: 35.9
    mcp: &id031
      status: none
    slug: split
    status: profiled
    tags: &id032
    - Experimentation
    - Feature Flags
    - Feature Management
    - Rollouts
    url: /providers/split/
  layer: common
  name: Split
  provider: split
  says: ships the Split SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.box.android/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-170.80
    key: AE-170.80
    name: Design & Creative Editing
    url: /capabilities/design-creative-editing/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 62.9
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id001
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe
    status: profiled
    tags: &id002
    - Adobe
    - Analytics
    - E-Signature
    - Fortune 1000
    url: /providers/adobe/
  layer: common
  name: Adobe Express
  provider: adobe
  says: lists Adobe Express as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 46.6
    band: exemplar
    in_catalog: true
    kin_score: 86.4
    mcp: &id005
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id006
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Anthropic (Claude)
  provider: anthropic
  says: lists Anthropic (Claude) as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620
    key: cybersecurity-management
    name: Cybersecurity Management
    url: /capabilities/cybersecurity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.8
    band: developing
    in_catalog: true
    kin_score: 53.8
    mcp: &id007
      source: https://github.com/Broadcom/rally-mcp-workflows
      status: verified
    slug: broadcom
    status: profiled
    tags: &id008
    - Cloud Infrastructure
    - Gateways
    - Management
    - Networks
    url: /providers/broadcom/
  layer: common
  name: Broadcom
  provider: broadcom
  says: lists Broadcom as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id011
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id012
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google
  provider: google-workspace
  says: lists Google as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.0
    band: strong
    in_catalog: true
    kin_score: 61.7
    mcp: &id013
      status: none
    slug: google-gemini
    status: profiled
    tags: &id014
    - AI Agents
    - Artificial Intelligence
    - Code Generation
    - Embeddings
    url: /providers/google-gemini/
  layer: agent
  name: Google Gemini
  provider: google-gemini
  says: lists Google Gemini as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.50.50
    key: BC-600.50.50
    name: End-User Computing Management
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id015
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id016
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: common
  name: Microsoft 365 (Copilot)
  provider: microsoft-365
  says: lists Microsoft 365 (Copilot) as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.20
    key: identity-access-management
    name: Identity & Access Management
    url: /capabilities/identity-access-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id017
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id018
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-110.10.10
    key: AE-110.10.10
    name: Hosted LLM Inference
    url: /capabilities/model-inference/
    via_parent: Model Inference
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 57.5
    band: exemplar
    in_catalog: true
    kin_score: 82.5
    mcp: &id019
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id020
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: OpenAI (ChatGPT)
  provider: openai
  says: lists OpenAI (ChatGPT) as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 11.4
    mcp: &id021
      status: none
    slug: netsuite
    status: profiled
    tags: &id022
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: common
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620
    key: cybersecurity-management
    name: Cybersecurity Management
    url: /capabilities/cybersecurity-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.5
    band: exemplar
    in_catalog: true
    kin_score: 68.8
    mcp: &id023
      source: https://github.com/PaloAltoNetworks/prisma-airs-mcp
      status: verified
    slug: palo-alto-networks
    status: profiled
    tags: &id024
    - Cloud Security
    - Cybersecurity
    - Firewall
    - Network Security
    url: /providers/palo-alto-networks/
  layer: common
  name: Palo Alto Networks
  provider: palo-alto-networks
  says: lists Palo Alto Networks as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-420
    key: customer-relationship-management
    name: Customer Relationship Management
    url: /capabilities/customer-relationship-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id027
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id028
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-850.10
    key: internal-communications-management
    name: Internal Communications Management
    url: /capabilities/internal-communications-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: exemplar
    in_catalog: true
    kin_score: 74.4
    mcp: &id029
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id030
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620
    key: cybersecurity-management
    name: Cybersecurity Management
    url: /capabilities/cybersecurity-management/
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
  layer: common
  name: Splunk
  provider: splunk
  says: lists Splunk as an integration
  source: https://www.box.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 54.7
    mcp: &id035
      status: none
    slug: workday
    status: profiled
    tags: &id036
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: common
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.box.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/cloud-storage-file-sync/box/
providers:
- agent_band: agent-ready
  agent_readiness: 62.9
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id001
  name: Adobe Express
  slug: adobe
  status: profiled
  tags: *id002
  url: /providers/adobe/
- agent_band: agent-ready
  agent_readiness: 56.9
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id003
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id004
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 46.6
  band: exemplar
  in_catalog: true
  kin_score: 86.4
  mcp: *id005
  name: Anthropic (Claude)
  slug: anthropic
  status: profiled
  tags: *id006
  url: /providers/anthropic/
- agent_band: agent-ready
  agent_readiness: 38.8
  band: developing
  in_catalog: true
  kin_score: 53.8
  mcp: *id007
  name: Broadcom
  slug: broadcom
  status: profiled
  tags: *id008
  url: /providers/broadcom/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id009
  name: Firebase (Crashlytics / Analytics)
  slug: google-firebase
  status: profiled
  tags: *id010
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id011
  name: Google
  slug: google-workspace
  status: profiled
  tags: *id012
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: strong
  in_catalog: true
  kin_score: 61.7
  mcp: *id013
  name: Google Gemini
  slug: google-gemini
  status: profiled
  tags: *id014
  url: /providers/google-gemini/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id015
  name: Microsoft 365 (Copilot)
  slug: microsoft-365
  status: profiled
  tags: *id016
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id017
  name: Okta
  slug: okta
  status: profiled
  tags: *id018
  url: /providers/okta/
- agent_band: agent-native
  agent_readiness: 57.5
  band: exemplar
  in_catalog: true
  kin_score: 82.5
  mcp: *id019
  name: OpenAI (ChatGPT)
  slug: openai
  status: profiled
  tags: *id020
  url: /providers/openai/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id021
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id022
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 38.5
  band: exemplar
  in_catalog: true
  kin_score: 68.8
  mcp: *id023
  name: Palo Alto Networks
  slug: palo-alto-networks
  status: profiled
  tags: *id024
  url: /providers/palo-alto-networks/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: strong
  in_catalog: true
  kin_score: 57.0
  mcp: *id025
  name: Pendo
  slug: pendoio
  status: profiled
  tags: *id026
  url: /providers/pendoio/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id027
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id028
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id029
  name: Slack
  slug: slack
  status: profiled
  tags: *id030
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: thin
  in_catalog: true
  kin_score: 35.9
  mcp: *id031
  name: Split
  slug: split
  status: profiled
  tags: *id032
  url: /providers/split/
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
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id035
  name: Workday
  slug: workday
  status: profiled
  tags: *id036
  url: /providers/workday/
siblings:
- name: Dropbox
  rows: 18
  url: /applications/cloud-storage-file-sync/dropbox/
- name: Filestash
  rows: 8
  url: /applications/cloud-storage-file-sync/filestash/
- name: Nextcloud
  rows: 32
  url: /applications/cloud-storage-file-sync/nextcloud/
- name: ownCloud Infinite Scale
  rows: 3
  url: /applications/cloud-storage-file-sync/owncloud-infinite-scale/
- name: rclone
  rows: 71
  url: /applications/cloud-storage-file-sync/rclone/
- name: Seafile
  rows: 8
  url: /applications/cloud-storage-file-sync/seafile/
- name: Syncthing
  rows: 2
  url: /applications/cloud-storage-file-sync/syncthing/
sitemap: true
title: 'Box: Cloud Storage & File Sync reference app'
---
