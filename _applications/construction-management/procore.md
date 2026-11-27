---
app: Procore
app_slug: procore
app_url: https://www.procore.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-1130
  key: engineering-document-management
  layer: domain
  name: Engineering Document Management
  providers:
  - Bluebeam
  url: /capabilities/engineering-document-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Microsoft Project
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-150.10
  key: contract-management
  layer: common
  name: Contract Management
  providers:
  - DocuSign
  url: /capabilities/contract-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - CMiC
  - Oracle NetSuite
  - QuickBooks Desktop
  - Sage 100 Contractor
  - Sage Intacct
  - Viewpoint Spectrum (Trimble)
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Google CrashLytics
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Google Firebase Analytics
  url: /capabilities/product-usage-analytics/
  via_parent: null
category:
  id: construction-management
  name: Construction Management
  url: /applications/construction-management/
counts:
  declared: 10
  observed: 2
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/bluebeam/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/cmic/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/docusign/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/microsoft-project/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/netsuite/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/quickbooks-desktop/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/sage-100/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/sage-300-cre/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/sage-intacct/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/viewpoint-spectrum/
- route: documentation
  url: https://v2.support.procore.com/en-au/product-manuals/xero/
- route: integrations page
  url: https://marketplace.procore.com/
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
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 62.0
    mcp: &id008
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id009
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Google CrashLytics
  provider: firebase
  says: ships the Google CrashLytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
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
  name: Google Firebase Analytics
  provider: firebase
  says: ships the Google Firebase Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.procore.activities/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-1130
    key: engineering-document-management
    name: Engineering Document Management
    url: /capabilities/engineering-document-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id002
      status: none
    slug: bluebeam
    status: profiled
    tags: &id003
    - Construction
    - Documents
    - PDF
    - Project Management
    url: /providers/bluebeam/
  layer: domain
  name: Bluebeam
  provider: bluebeam
  says: lists Bluebeam as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/bluebeam/
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
    agent_band: agent-aware
    agent_readiness: 28.2
    band: thin
    in_catalog: true
    kin_score: 37.7
    mcp: &id004
      status: unknown
    slug: cmic
    status: profiled
    tags: &id005
    - Construction
    - ERP
    - Finance
    - Project Management
    url: /providers/cmic/
  layer: common
  name: CMiC
  provider: cmic
  says: lists CMiC as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/cmic/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.7
    band: exemplar
    in_catalog: true
    kin_score: 71.5
    mcp: &id006
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id007
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
  layer: common
  name: DocuSign
  provider: docusign
  says: lists DocuSign as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/docusign/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-900.30
    key: project-management
    name: Project Management
    url: /capabilities/project-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.5
    band: strong
    in_catalog: true
    kin_score: 56.3
    mcp: &id010
      status: none
    slug: microsoft-project
    status: profiled
    tags: &id011
    - Budgeting
    - Gantt Charts
    - Microsoft
    - Project Management
    url: /providers/microsoft-project/
  layer: domain
  name: Microsoft Project
  provider: microsoft-project
  says: lists Microsoft Project as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/microsoft-project/
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
    mcp: &id012
      status: none
    slug: netsuite
    status: profiled
    tags: &id013
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: common
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/netsuite/
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
    agent_band: agent-ready
    agent_readiness: 38.3
    band: strong
    in_catalog: true
    kin_score: 59.8
    mcp: &id014
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id015
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks Desktop
  provider: quickbooks
  says: lists QuickBooks Desktop as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/quickbooks-desktop/
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
    agent_band: agent-ready
    agent_readiness: 30.6
    band: developing
    in_catalog: true
    kin_score: 41.7
    mcp: &id016
      status: none
    slug: sage
    status: profiled
    tags: &id017
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: common
  name: Sage 100 Contractor
  provider: sage
  says: lists Sage 100 Contractor as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/sage-100/
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
    agent_band: agent-aware
    agent_readiness: 15.1
    band: thin
    in_catalog: true
    kin_score: 26.5
    mcp: &id018
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id019
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: common
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/sage-intacct/
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
    agent_band: agent-ready
    agent_readiness: 35.3
    band: exemplar
    in_catalog: true
    kin_score: 66.6
    mcp: &id020
      status: none
    slug: trimble
    status: profiled
    tags: &id021
    - Construction
    - GPS
    - Geospatial
    - Transportation
    url: /providers/trimble/
  layer: common
  name: Viewpoint Spectrum (Trimble)
  provider: trimble
  says: lists Viewpoint Spectrum (Trimble) as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/viewpoint-spectrum/
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
    agent_band: agent-native
    agent_readiness: 60.0
    band: exemplar
    in_catalog: true
    kin_score: 87.1
    mcp: &id022
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id023
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://v2.support.procore.com/en-au/product-manuals/xero/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/construction-management/procore/
providers:
- agent_band: agent-ready
  agent_readiness: 30.3
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id002
  name: Bluebeam
  slug: bluebeam
  status: profiled
  tags: *id003
  url: /providers/bluebeam/
- agent_band: agent-aware
  agent_readiness: 28.2
  band: thin
  in_catalog: true
  kin_score: 37.7
  mcp: *id004
  name: CMiC
  slug: cmic
  status: profiled
  tags: *id005
  url: /providers/cmic/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 71.5
  mcp: *id006
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id007
  url: /providers/docusign/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id008
  name: Google CrashLytics
  slug: google-firebase
  status: profiled
  tags: *id009
  url: /providers/google-firebase/
- agent_band: agent-aware
  agent_readiness: 26.5
  band: strong
  in_catalog: true
  kin_score: 56.3
  mcp: *id010
  name: Microsoft Project
  slug: microsoft-project
  status: profiled
  tags: *id011
  url: /providers/microsoft-project/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id012
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id013
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id014
  name: QuickBooks Desktop
  slug: quickbooks
  status: profiled
  tags: *id015
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id016
  name: Sage 100 Contractor
  slug: sage
  status: profiled
  tags: *id017
  url: /providers/sage/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id018
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id019
  url: /providers/sage-intacct/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: exemplar
  in_catalog: true
  kin_score: 66.6
  mcp: *id020
  name: Viewpoint Spectrum (Trimble)
  slug: trimble
  status: profiled
  tags: *id021
  url: /providers/trimble/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id022
  name: Xero
  slug: xero
  status: profiled
  tags: *id023
  url: /providers/xero/
siblings:
- name: CompanyCam
  rows: 15
  url: /applications/construction-management/companycam/
- name: JobTread
  rows: 11
  url: /applications/construction-management/jobtread/
- name: Knowify
  rows: 9
  url: /applications/construction-management/knowify/
- name: OpenProject (BIM)
  rows: 7
  url: /applications/construction-management/openproject-bim/
- name: Raken
  rows: 21
  url: /applications/construction-management/raken/
- name: Siteline
  rows: 11
  url: /applications/construction-management/siteline/
sitemap: true
title: 'Procore: Construction Management reference app'
---
