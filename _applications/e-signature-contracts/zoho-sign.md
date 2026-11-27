---
app: Zoho Sign
app_slug: zoho-sign
app_url: https://www.zoho.com/sign/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-160.80
  key: AE-160.80
  layer: domain
  name: Qualified Electronic Signatures & Trust Services
  providers:
  - Aadhaar eSign (UIDAI)
  - eID Easy
  - eMudhra
  - InfoCert
  - Signicat
  - Singpass
  - Uanataca
  url: /capabilities/qualified-electronic-signatures-trust-services/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Box
  - Dropbox
  - Google Drive
  - Google Workspace
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - HubSpot
  - Pipedrive
  - Vtiger
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2500.50
  key: electronic-documentation-management
  layer: common
  name: Electronic Documentation Management
  providers:
  - Formstack
  - Microsoft 365
  url: /capabilities/electronic-documentation-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-850.10
  key: internal-communications-management
  layer: common
  name: Internal Communications Management
  providers:
  - Microsoft Teams
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Integrately
  - Make
  - Power Automate
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: e-signature-contracts
  name: E-signature & Contract Management
  url: /applications/e-signature-contracts/
counts:
  declared: 24
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.zoho.com/sign/integrations.html
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.8
    band: minimal
    in_catalog: true
    kin_score: 10.6
    mcp: &id001
      status: unknown
    slug: uidai
    status: profiled
    tags: &id002
    - Authentication
    - Digital Signature
    - Government
    - Identity
    url: /providers/uidai/
  layer: domain
  name: Aadhaar eSign (UIDAI)
  provider: uidai
  says: lists Aadhaar eSign (UIDAI) as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    mcp: &id003
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id004
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: common
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    mcp: &id005
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id006
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.3
    band: thin
    in_catalog: true
    kin_score: 30.9
    mcp: &id007
      source: https://github.com/eideasy/eideasy-mcp
      status: verified
    slug: eid-easy
    status: profiled
    tags: &id008
    - Company
    - E-Signature
    - eID
    - eSealing
    url: /providers/eid-easy/
  layer: domain
  name: eID Easy
  provider: eid-easy
  says: lists eID Easy as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.6
    mcp: &id009
      status: none
    slug: emudhra
    status: profiled
    tags: &id010
    - Company
    - Digital Trust
    - Enterprise Software
    - PKI
    url: /providers/emudhra/
  layer: domain
  name: eMudhra
  provider: emudhra
  says: lists eMudhra as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2500.50
    key: electronic-documentation-management
    name: Electronic Documentation Management
    url: /capabilities/electronic-documentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.2
    band: emerging
    in_catalog: true
    kin_score: 24.4
    mcp: &id011
      status: none
    slug: formstack
    status: profiled
    tags: &id012
    - Documents
    - E-Signature
    - Forms
    - Workflow Automation
    url: /providers/formstack/
  layer: common
  name: Formstack
  provider: formstack
  says: lists Formstack as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 43.2
    band: exemplar
    in_catalog: true
    kin_score: 66.8
    mcp: &id013
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id014
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: common
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    mcp: &id015
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id016
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: common
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 43.0
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id017
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id018
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id019
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id020
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: common
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 34.1
    band: developing
    in_catalog: true
    kin_score: 52.2
    mcp: &id021
      status: unknown
    slug: infocert
    status: profiled
    tags: &id022
    - Company
    - Digital Identity
    - Digital Trust
    - E-Signature
    url: /providers/infocert/
  layer: domain
  name: InfoCert
  provider: infocert
  says: lists InfoCert as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_band: agent-aware
    agent_readiness: 19.4
    band: developing
    in_catalog: true
    kin_score: 45.4
    mcp: &id023
      status: none
    slug: integrately
    status: profiled
    tags: &id024
    - Automation
    - Business Process Automation
    - No-Code
    - iPaaS
    url: /providers/integrately/
  layer: common
  name: Integrately
  provider: integrately
  says: lists Integrately as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 43.0
    band: developing
    in_catalog: true
    kin_score: 43.4
    mcp: &id025
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id026
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2500.50
    key: electronic-documentation-management
    name: Electronic Documentation Management
    url: /capabilities/electronic-documentation-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id027
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id028
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: common
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 30.5
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id029
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id030
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    mcp: &id031
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id032
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: common
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 42.9
    band: exemplar
    in_catalog: true
    kin_score: 70.8
    mcp: &id033
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id034
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: common
  name: Outlook
  provider: microsoft-outlook
  says: lists Outlook as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 28.7
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id035
      status: none
    slug: pipedrive
    status: profiled
    tags: &id036
    - CRM
    - Pipeline Management
    - Sales
    - Software-as-a-Service
    url: /providers/pipedrive/
  layer: common
  name: Pipedrive
  provider: pipedrive
  says: lists Pipedrive as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 29.1
    band: strong
    in_catalog: true
    kin_score: 62.1
    mcp: &id037
      status: none
    slug: microsoft-power-automate
    status: profiled
    tags: &id038
    - Automation
    - Business Process
    - Integration
    - Low-Code
    url: /providers/microsoft-power-automate/
  layer: common
  name: Power Automate
  provider: microsoft-power-automate
  says: lists Power Automate as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.6
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id039
      status: none
    slug: signicat
    status: profiled
    tags: &id040
    - Authentication
    - Company
    - Digital Identity
    - E-Signature
    url: /providers/signicat/
  layer: domain
  name: Signicat
  provider: signicat
  says: lists Signicat as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 5.3
    band: thin
    in_catalog: true
    kin_score: 27.0
    mcp: &id041
      status: none
    slug: singpass
    status: profiled
    tags: &id042
    - Authentication
    - Company
    - Government
    - Identity
    url: /providers/singpass/
  layer: domain
  name: Singpass
  provider: singpass
  says: lists Singpass as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-160.80
    key: AE-160.80
    name: Qualified Electronic Signatures & Trust Services
    url: /capabilities/qualified-electronic-signatures-trust-services/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 13.5
    mcp: &id043
      status: unknown
    slug: uanataca
    status: profiled
    tags: &id044
    - Company
    - Digital Identity
    - E-Signature
    - Wallets
    url: /providers/uanataca/
  layer: domain
  name: Uanataca
  provider: uanataca
  says: lists Uanataca as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_band: agent-aware
    agent_readiness: 10.6
    band: thin
    in_catalog: true
    kin_score: 34.7
    mcp: &id045
      status: none
    slug: vtiger
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - CRM
    - Company
    - Sales
    url: /providers/vtiger/
  layer: common
  name: Vtiger
  provider: vtiger
  says: lists Vtiger as an integration
  source: https://www.zoho.com/sign/integrations.html
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
    agent_readiness: 66.1
    band: exemplar
    in_catalog: true
    kin_score: 72.9
    mcp: &id047
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id048
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.zoho.com/sign/integrations.html
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/e-signature-contracts/zoho-sign/
providers:
- agent_band: human-only
  agent_readiness: 2.8
  band: minimal
  in_catalog: true
  kin_score: 10.6
  mcp: *id001
  name: Aadhaar eSign (UIDAI)
  slug: uidai
  status: profiled
  tags: *id002
  url: /providers/uidai/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id003
  name: Box
  slug: box
  status: profiled
  tags: *id004
  url: /providers/box/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id005
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id006
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 6.3
  band: thin
  in_catalog: true
  kin_score: 30.9
  mcp: *id007
  name: eID Easy
  slug: eid-easy
  status: profiled
  tags: *id008
  url: /providers/eid-easy/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.6
  mcp: *id009
  name: eMudhra
  slug: emudhra
  status: profiled
  tags: *id010
  url: /providers/emudhra/
- agent_band: agent-ready
  agent_readiness: 33.2
  band: emerging
  in_catalog: true
  kin_score: 24.4
  mcp: *id011
  name: Formstack
  slug: formstack
  status: profiled
  tags: *id012
  url: /providers/formstack/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id013
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id014
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id015
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id016
  url: /providers/google-drive/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id017
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id018
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id019
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id020
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 34.1
  band: developing
  in_catalog: true
  kin_score: 52.2
  mcp: *id021
  name: InfoCert
  slug: infocert
  status: profiled
  tags: *id022
  url: /providers/infocert/
- agent_band: agent-aware
  agent_readiness: 19.4
  band: developing
  in_catalog: true
  kin_score: 45.4
  mcp: *id023
  name: Integrately
  slug: integrately
  status: profiled
  tags: *id024
  url: /providers/integrately/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id025
  name: Make
  slug: make
  status: profiled
  tags: *id026
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id027
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id028
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 30.5
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id029
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id030
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id031
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id032
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id033
  name: Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id034
  url: /providers/microsoft-outlook/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id035
  name: Pipedrive
  slug: pipedrive
  status: profiled
  tags: *id036
  url: /providers/pipedrive/
- agent_band: agent-ready
  agent_readiness: 29.1
  band: strong
  in_catalog: true
  kin_score: 62.1
  mcp: *id037
  name: Power Automate
  slug: microsoft-power-automate
  status: profiled
  tags: *id038
  url: /providers/microsoft-power-automate/
- agent_band: agent-ready
  agent_readiness: 35.6
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id039
  name: Signicat
  slug: signicat
  status: profiled
  tags: *id040
  url: /providers/signicat/
- agent_band: agent-aware
  agent_readiness: 5.3
  band: thin
  in_catalog: true
  kin_score: 27.0
  mcp: *id041
  name: Singpass
  slug: singpass
  status: profiled
  tags: *id042
  url: /providers/singpass/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 13.5
  mcp: *id043
  name: Uanataca
  slug: uanataca
  status: profiled
  tags: *id044
  url: /providers/uanataca/
- agent_band: agent-aware
  agent_readiness: 10.6
  band: thin
  in_catalog: true
  kin_score: 34.7
  mcp: *id045
  name: Vtiger
  slug: vtiger
  status: profiled
  tags: *id046
  url: /providers/vtiger/
- agent_band: agent-ready
  agent_readiness: 66.1
  band: exemplar
  in_catalog: true
  kin_score: 72.9
  mcp: *id047
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id048
  url: /providers/zapier/
siblings:
- name: Documenso
  rows: 15
  url: /applications/e-signature-contracts/documenso/
- name: DocuSeal
  rows: 4
  url: /applications/e-signature-contracts/docuseal/
- name: DocuSign
  rows: 16
  url: /applications/e-signature-contracts/docusign/
- name: Dropbox Sign
  rows: 18
  url: /applications/e-signature-contracts/dropbox-sign/
- name: OpenSign
  rows: 7
  url: /applications/e-signature-contracts/opensign/
sitemap: true
title: 'Zoho Sign: E-signature & Contract Management reference app'
---
