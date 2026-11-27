---
app: Vendr
app_slug: vendr
app_url: https://www.vendr.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Google Drive
  - Microsoft OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-150.10
  key: contract-management
  layer: domain
  name: Contract Management
  providers:
  - DocuSign
  - Ironclad
  url: /capabilities/contract-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - NetSuite
  - QuickBooks
  - Sage Intacct
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - BambooHR
  - Gusto
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: domain
  name: IT Service Management
  providers:
  - Jira Service Management
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.70
  key: it-vendor-management
  layer: domain
  name: IT Vendor Management
  providers:
  - Google Chrome
  url: /capabilities/it-vendor-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: domain
  name: Internal Communications Management
  providers:
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Azure Active Directory
  - Google Workspace
  - JumpCloud
  - Okta
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: procurement-spend
  name: Procurement & Spend Management
  url: /applications/procurement-spend/
counts:
  declared: 20
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.vendr.com/integrations
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id001
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id002
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Azure Active Directory
  provider: microsoft-entra
  says: lists Azure Active Directory as an integration
  source: https://www.vendr.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 26.3
    band: developing
    in_catalog: true
    kin_score: 40.7
    mcp: &id003
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id004
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
  layer: domain
  name: BambooHR
  provider: bamboohr
  says: lists BambooHR as an integration
  source: https://www.vendr.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id005
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id007
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id008
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
  layer: domain
  name: DocuSign
  provider: docusign
  says: lists DocuSign as an integration
  source: https://www.vendr.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.8
    band: developing
    in_catalog: true
    kin_score: 45.9
    mcp: &id009
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.vendr.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.70
    key: it-vendor-management
    name: IT Vendor Management
    url: /capabilities/it-vendor-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.9
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id011
      source: https://github.com/ChromeDevTools/chrome-devtools-mcp
      status: verified
    slug: google-chrome
    status: profiled
    tags: &id012
    - Browser
    - Chrome Extensions
    - Developer Tools
    - Web Platform
    url: /providers/google-chrome/
  layer: domain
  name: Google Chrome
  provider: google-chrome
  says: lists Google Chrome as an integration
  source: https://www.vendr.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 44.4
    band: exemplar
    in_catalog: true
    kin_score: 73.2
    mcp: &id013
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id014
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id015
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id016
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: domain
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.vendr.com/integrations
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
    agent_readiness: 31.7
    band: developing
    in_catalog: true
    kin_score: 44.9
    mcp: &id017
      status: none
    slug: gusto
    status: profiled
    tags: &id018
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: domain
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://www.vendr.com/integrations
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
    agent_readiness: 35.0
    band: developing
    in_catalog: true
    kin_score: 52.3
    mcp: &id019
      status: none
    slug: ironclad
    status: profiled
    tags: &id020
    - Contract Lifecycle Management
    - Contracts
    - Legal Tech
    - LegalOps
    url: /providers/ironclad/
  layer: domain
  name: Ironclad
  provider: ironclad
  says: lists Ironclad as an integration
  source: https://www.vendr.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-600.30
    key: it-service-management
    name: IT Service Management
    url: /capabilities/it-service-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 64.4
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id021
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id022
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira Service Management
  provider: jira
  says: lists Jira Service Management as an integration
  source: https://www.vendr.com/integrations
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
    agent_readiness: 31.3
    band: thin
    in_catalog: true
    kin_score: 33.6
    mcp: &id023
      source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
      status: verified
    slug: jumpcloud
    status: profiled
    tags: &id024
    - Directory Services
    - Identity
    - MFA
    - SSO
    url: /providers/jumpcloud/
  layer: domain
  name: JumpCloud
  provider: jumpcloud
  says: lists JumpCloud as an integration
  source: https://www.vendr.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-916
    key: AE-916
    name: Cloud Drive & File Sync
    url: /capabilities/it-infrastructure-management/
    via_parent: IT Infrastructure Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.9
    band: developing
    in_catalog: true
    kin_score: 50.9
    mcp: &id025
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id026
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: lists Microsoft OneDrive as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id027
      status: none
    slug: netsuite
    status: profiled
    tags: &id028
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: NetSuite
  provider: netsuite
  says: lists NetSuite as an integration
  source: https://www.vendr.com/integrations
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
    agent_readiness: 47.1
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id029
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id030
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.vendr.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 24.3
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id031
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id032
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: domain
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id033
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id034
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id035
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id036
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id037
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id038
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.vendr.com/integrations
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
    mcp: &id039
      status: none
    slug: workday
    status: profiled
    tags: &id040
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.vendr.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/procurement-spend/vendr/
providers:
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id001
  name: Azure Active Directory
  slug: microsoft-entra
  status: profiled
  tags: *id002
  url: /providers/microsoft-entra/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id003
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id004
  url: /providers/bamboohr/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id005
  name: Box
  slug: box
  status: profiled
  tags: *id006
  url: /providers/box/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 71.5
  mcp: *id007
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id008
  url: /providers/docusign/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id009
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id010
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id011
  name: Google Chrome
  slug: google-chrome
  status: profiled
  tags: *id012
  url: /providers/google-chrome/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id013
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id014
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id015
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id016
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 31.7
  band: developing
  in_catalog: true
  kin_score: 44.9
  mcp: *id017
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id018
  url: /providers/gusto/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id019
  name: Ironclad
  slug: ironclad
  status: profiled
  tags: *id020
  url: /providers/ironclad/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id021
  name: Jira Service Management
  slug: jira
  status: profiled
  tags: *id022
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id023
  name: JumpCloud
  slug: jumpcloud
  status: profiled
  tags: *id024
  url: /providers/jumpcloud/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id025
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id026
  url: /providers/microsoft-onedrive/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id027
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id028
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id029
  name: Okta
  slug: okta
  status: profiled
  tags: *id030
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id031
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id032
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id033
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id034
  url: /providers/quickbooks/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id035
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id036
  url: /providers/sage-intacct/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id037
  name: Slack
  slug: slack
  status: profiled
  tags: *id038
  url: /providers/slack/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id039
  name: Workday
  slug: workday
  status: profiled
  tags: *id040
  url: /providers/workday/
siblings:
- name: ERPNext (Buying module)
  rows: 5
  url: /applications/procurement-spend/erpnext-buying-module/
- name: Odoo Purchase
  rows: 1
  url: /applications/procurement-spend/odoo-purchase/
- name: Precoro
  rows: 10
  url: /applications/procurement-spend/precoro/
- name: Procurify
  rows: 10
  url: /applications/procurement-spend/procurify/
- name: Spendflo
  rows: 46
  url: /applications/procurement-spend/spendflo/
- name: Tradogram
  rows: 32
  url: /applications/procurement-spend/tradogram/
sitemap: true
title: 'Vendr: Procurement & Spend Management reference app'
---
