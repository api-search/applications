---
app: IDrive
app_slug: idrive
app_url: https://www.idrive.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-160.20.20
  key: BC-160.20.20
  layer: domain
  name: Backup and Restore Management
  providers:
  - Box
  - Dropbox
  - Google Workspace
  - Microsoft 365
  - Microsoft Entra ID
  - Salesforce
  url: /capabilities/disaster-recovery-management/
  via_parent: Disaster Recovery Management
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Firebase
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Firebase
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: backup
  name: Backup & Device Restore
  url: /applications/backup/
counts:
  declared: 6
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
- route: integrations page
  url: https://www.idrive.com/
integrations:
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id006
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id007
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Firebase
  provider: firebase
  says: ships the Firebase SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.prosoftnet.android.idriveonline/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.4
    band: strong
    in_catalog: true
    kin_score: 65.5
    mcp: &id002
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id003
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.idrive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id004
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id005
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.idrive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id008
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id009
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: domain
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.idrive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.7
    band: strong
    in_catalog: true
    kin_score: 64.4
    mcp: &id010
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id011
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://www.idrive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id012
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id013
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Entra ID
  provider: microsoft-entra
  says: lists Microsoft Entra ID as an integration
  source: https://www.idrive.com/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-160.20.20
    key: BC-160.20.20
    name: Backup and Restore Management
    url: /capabilities/disaster-recovery-management/
    via_parent: Disaster Recovery Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 54.7
    band: exemplar
    in_catalog: true
    kin_score: 90.6
    mcp: &id014
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id015
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.idrive.com/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/backup/idrive/
providers:
- agent_band: agent-ready
  agent_readiness: 57.4
  band: strong
  in_catalog: true
  kin_score: 65.5
  mcp: *id002
  name: Box
  slug: box
  status: profiled
  tags: *id003
  url: /providers/box/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id004
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id005
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id006
  name: Firebase
  slug: firebase
  status: profiled
  tags: *id007
  url: /providers/firebase/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id008
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id009
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 36.7
  band: strong
  in_catalog: true
  kin_score: 64.4
  mcp: *id010
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id011
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id012
  name: Microsoft Entra ID
  slug: microsoft-entra
  status: profiled
  tags: *id013
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 54.7
  band: exemplar
  in_catalog: true
  kin_score: 90.6
  mcp: *id014
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id015
  url: /providers/salesforce/
siblings:
- name: Arq Backup
  rows: 11
  url: /applications/backup/arq-backup/
- name: Backblaze Computer Backup
  rows: 2
  url: /applications/backup/backblaze-computer-backup/
- name: Backrest
  rows: 5
  url: /applications/backup/backrest/
- name: borgmatic
  rows: 9
  url: /applications/backup/borgmatic/
- name: Duplicati
  rows: 31
  url: /applications/backup/duplicati/
- name: Kopia
  rows: 6
  url: /applications/backup/kopia/
- name: Restic
  rows: 5
  url: /applications/backup/restic/
- name: Velero
  rows: 20
  url: /applications/backup/velero/
sitemap: true
title: 'IDrive: Backup & Device Restore reference app'
---
