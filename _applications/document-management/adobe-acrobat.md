---
app: Adobe Acrobat
app_slug: adobe-acrobat
app_url: https://www.adobe.com/acrobat.html
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
  - Egnyte Connect
  - Google Drive
  - Microsoft 365
  - Microsoft OneDrive
  - Zoho Docs
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-150.10
  key: contract-management
  layer: domain
  name: Contract Management
  providers:
  - Agiloft
  - Icertis
  - Ironclad
  url: /capabilities/contract-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-917
  key: AE-917
  layer: domain
  name: Enterprise Content & Document Management
  providers:
  - Hyland
  - Laser Fiche
  - M-Files
  - Microsoft SharePoint
  url: /capabilities/it-application-management/
  via_parent: IT Application Management
- attribution: Turbo EA
  id: BC-420
  key: customer-relationship-management
  layer: common
  name: Customer Relationship Management
  providers:
  - Microsoft Dynamics 365
  - Salesforce
  url: /capabilities/customer-relationship-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - Xero
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
  id: BC-600.30
  key: it-service-management
  layer: common
  name: IT Service Management
  providers:
  - ServiceNow
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-903
  key: AE-903
  layer: common
  name: In-App Ad Monetisation
  providers:
  - Google AdMob
  url: /capabilities/in-app-ad-monetisation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-902
  key: AE-902
  layer: common
  name: Mobile Attribution & Deep Linking
  providers:
  - Branch
  url: /capabilities/mobile-attribution-deep-linking/
  via_parent: null
- attribution: Turbo EA
  id: BC-500
  key: procurement-management
  layer: common
  name: Procurement Management
  providers:
  - SAP Ariba
  url: /capabilities/procurement-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Adobe Experience Cloud
  - Facebook Analytics
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-160.10.30
  key: AE-160.10.30
  layer: common
  name: Social & Federated Login
  providers:
  - Facebook Login / Share
  url: /capabilities/customer-sign-in/
  via_parent: Customer Sign-In
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: common
  name: Tenant Identity Federation
  providers:
  - Okta
  url: /capabilities/tenant-identity-federation/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Make
  - Nintex Workflow Cloud
  - ProcessMaker
  - UiPath
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
category:
  id: document-management
  name: Document Management & OCR
  url: /applications/document-management/
counts:
  declared: 25
  observed: 6
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
- route: integrations page
  url: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 53.0
    band: strong
    in_catalog: true
    kin_score: 65.1
    mcp: &id002
      source: https://github.com/adobe/cq-quickstart-mcp-server
      status: verified
    slug: adobe-experience-cloud
    status: profiled
    tags: &id003
    - Analytics
    - Customer Experience
    - Digital Marketing
    - Personalization
    url: /providers/adobe-experience-cloud/
  layer: common
  name: Adobe Experience Cloud
  provider: adobe-experience-cloud
  says: ships the Adobe Experience Cloud SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-902
    key: AE-902
    name: Mobile Attribution & Deep Linking
    url: /capabilities/mobile-attribution-deep-linking/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 21.9
    band: thin
    in_catalog: true
    kin_score: 33.8
    mcp: &id008
      status: none
    slug: branch-io
    status: profiled
    tags: &id009
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4280.30
    key: product-usage-analytics
    name: Product Usage Analytics
    url: /capabilities/product-usage-analytics/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: &id001
    agent_band: agent-aware
    agent_readiness: 28.1
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id014
      status: none
    slug: facebook
    status: profiled
    tags: &id015
    - Advertising
    - Content Publishing
    - Facebook
    - Fortune 500
    url: /providers/facebook/
  layer: common
  name: Facebook Analytics
  provider: facebook
  says: ships the Facebook Analytics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-160.10.30
    key: AE-160.10.30
    name: Social & Federated Login
    url: /capabilities/customer-sign-in/
    via_parent: Customer Sign-In
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts: *id001
  layer: common
  name: Facebook Login / Share
  provider: facebook
  says: ships the Facebook Login / Share SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
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
    mcp: &id016
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: google-firebase
    status: profiled
    tags: &id017
    - Analytics
    - Authentication
    - Backend-as-a-Service
    - Cloud Messaging
    url: /providers/google-firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
  tier: observed
- capability:
    attribution: API Evangelist extension
    id: AE-903
    key: AE-903
    name: In-App Ad Monetisation
    url: /capabilities/in-app-ad-monetisation/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 35.3
    band: strong
    in_catalog: true
    kin_score: 65.2
    mcp: &id018
      status: none
    slug: google-admob
    status: profiled
    tags: &id019
    - Ad Mediation
    - AdMob
    - Advertising
    - App Monetization
    url: /providers/google-admob/
  layer: common
  name: Google AdMob
  provider: google-admob
  says: ships the Google AdMob SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.adobe.reader/latest/
  tier: observed
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
    agent_readiness: 31.5
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id004
      status: none
    slug: agiloft
    status: profiled
    tags: &id005
    - Contract Lifecycle Management
    - Contract Management
    - Legal
    - Procurement
    url: /providers/agiloft/
  layer: domain
  name: Agiloft
  provider: agiloft
  says: lists Agiloft as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id006
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id007
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id010
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id011
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 26.4
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id012
      source: https://github.com/egnyte/egnyte-mcp-server
      status: verified
    slug: egnyte
    status: profiled
    tags: &id013
    - Content Collaboration
    - Document Management
    - Enterprise Storage
    - File Sharing
    url: /providers/egnyte/
  layer: domain
  name: Egnyte Connect
  provider: egnyte
  says: lists Egnyte Connect as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id020
      source: https://github.com/google/mcp
      status: verified
    slug: google-drive
    status: profiled
    tags: &id021
    - Cloud Storage
    - Collaboration
    - Document Management
    - Drives
    url: /providers/google-drive/
  layer: domain
  name: Google Drive
  provider: google-drive
  says: lists Google Drive as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id022
      status: unchecked
    slug: hyland
    status: queued for profiling
    tags: &id023 []
    url: null
  layer: domain
  name: Hyland
  provider: hyland
  says: lists Hyland as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 12.9
    mcp: &id024
      status: none
    slug: icertis
    status: profiled
    tags: &id025
    - Company
    - Contract Intelligence
    - Contract Lifecycle Management
    - Enterprise
    url: /providers/icertis/
  layer: domain
  name: Icertis
  provider: icertis
  says: lists Icertis as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id026
      status: none
    slug: ironclad
    status: profiled
    tags: &id027
    - Contract Lifecycle Management
    - Contracts
    - Legal Tech
    - LegalOps
    url: /providers/ironclad/
  layer: domain
  name: Ironclad
  provider: ironclad
  says: lists Ironclad as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 14.8
    band: developing
    in_catalog: true
    kin_score: 48.3
    mcp: &id028
      status: none
    slug: laserfiche
    status: profiled
    tags: &id029
    - Company
    - Document Management
    - Enterprise Content Management
    - Process Automation
    url: /providers/laserfiche/
  layer: domain
  name: Laser Fiche
  provider: laserfiche
  says: lists Laser Fiche as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id030
      status: none
    slug: m-files
    status: profiled
    tags: &id031
    - Company
    - Document Management
    - Information Management
    - Infrastructure Saas
    url: /providers/m-files/
  layer: domain
  name: M-Files
  provider: m-files
  says: lists M-Files as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id032
      source: https://github.com/integromat/make-mcp-server
      status: verified
    slug: make
    status: profiled
    tags: &id033
    - Automation
    - Integration
    - No-Code
    - iPaaS
    url: /providers/make/
  layer: common
  name: Make
  provider: make
  says: lists Make as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 36.3
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id034
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id035
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id036
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id037
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: common
  name: Microsoft Dynamics 365
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics 365 as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id038
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id039
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: Microsoft OneDrive
  provider: microsoft-onedrive
  says: lists Microsoft OneDrive as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-917
    key: AE-917
    name: Enterprise Content & Document Management
    url: /capabilities/it-application-management/
    via_parent: IT Application Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 32.3
    band: strong
    in_catalog: true
    kin_score: 60.9
    mcp: &id040
      source: https://github.com/microsoft/mcp
      status: verified
    slug: sharepoint
    status: profiled
    tags: &id041
    - Collaboration
    - Document Management
    - Enterprise Content Management
    - Intranet
    url: /providers/sharepoint/
  layer: domain
  name: Microsoft SharePoint
  provider: sharepoint
  says: lists Microsoft SharePoint as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 19.9
    mcp: &id042
      status: none
    slug: nintex
    status: profiled
    tags: &id043
    - Automation
    - Company
    - Low-Code
    - Workflows
    url: /providers/nintex/
  layer: common
  name: Nintex Workflow Cloud
  provider: nintex
  says: lists Nintex Workflow Cloud as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id044
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id045
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 29.5
    band: thin
    in_catalog: true
    kin_score: 28.9
    mcp: &id046
      status: none
    slug: processmaker
    status: profiled
    tags: &id047
    - BPMN 2.0
    - Business Process Management
    - Low-Code
    - Workflow Automation
    url: /providers/processmaker/
  layer: common
  name: ProcessMaker
  provider: processmaker
  says: lists ProcessMaker as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id048
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id049
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: common
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-500
    key: procurement-management
    name: Procurement Management
    url: /capabilities/procurement-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.0
    band: developing
    in_catalog: true
    kin_score: 45.7
    mcp: &id050
      status: none
    slug: ariba
    status: profiled
    tags: &id051
    - B2B
    - Catalog Management
    - Compliance
    - Contracts
    url: /providers/ariba/
  layer: common
  name: SAP Ariba
  provider: ariba
  says: lists SAP Ariba as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 42.3
    band: strong
    in_catalog: true
    kin_score: 61.9
    mcp: &id052
      status: none
    slug: servicenow
    status: profiled
    tags: &id053
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: common
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_readiness: 34.5
    band: exemplar
    in_catalog: true
    kin_score: 71.0
    mcp: &id054
      source: https://github.com/UiPath/uipath-mcp-python
      status: verified
    slug: uipath
    status: profiled
    tags: &id055
    - Artificial Intelligence
    - Automation
    - Document Processing
    - RPA
    url: /providers/uipath/
  layer: common
  name: UiPath
  provider: uipath
  says: lists UiPath as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id056
      status: none
    slug: workday
    status: profiled
    tags: &id057
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: common
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    mcp: &id058
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id059
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 23.7
    mcp: &id060
      source: https://www.zoho.com/workdrive/mcp.html
      status: verified
    slug: zoho-workdrive
    status: profiled
    tags: &id061
    - Cloud Storage
    - Collaboration
    - File Management
    - Zoho
    url: /providers/zoho-workdrive/
  layer: domain
  name: Zoho Docs
  provider: zoho-workdrive
  says: lists Zoho Docs as an integration
  source: https://www.adobe.com/acrobat/business/integrations.html
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/document-management/adobe-acrobat/
providers:
- agent_band: agent-ready
  agent_readiness: 53.0
  band: strong
  in_catalog: true
  kin_score: 65.1
  mcp: *id002
  name: Adobe Experience Cloud
  slug: adobe-experience-cloud
  status: profiled
  tags: *id003
  url: /providers/adobe-experience-cloud/
- agent_band: agent-ready
  agent_readiness: 31.5
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id004
  name: Agiloft
  slug: agiloft
  status: profiled
  tags: *id005
  url: /providers/agiloft/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id006
  name: Box
  slug: box
  status: profiled
  tags: *id007
  url: /providers/box/
- agent_band: agent-aware
  agent_readiness: 21.9
  band: thin
  in_catalog: true
  kin_score: 33.8
  mcp: *id008
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id009
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id010
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id011
  url: /providers/dropbox/
- agent_band: agent-aware
  agent_readiness: 26.4
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id012
  name: Egnyte Connect
  slug: egnyte
  status: profiled
  tags: *id013
  url: /providers/egnyte/
- agent_band: agent-aware
  agent_readiness: 28.1
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id014
  name: Facebook Analytics
  slug: facebook
  status: profiled
  tags: *id015
  url: /providers/facebook/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: strong
  in_catalog: true
  kin_score: 62.0
  mcp: *id016
  name: Firebase (Crashlytics / Analytics)
  slug: google-firebase
  status: profiled
  tags: *id017
  url: /providers/google-firebase/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: strong
  in_catalog: true
  kin_score: 65.2
  mcp: *id018
  name: Google AdMob
  slug: google-admob
  status: profiled
  tags: *id019
  url: /providers/google-admob/
- agent_band: agent-ready
  agent_readiness: 44.4
  band: exemplar
  in_catalog: true
  kin_score: 73.2
  mcp: *id020
  name: Google Drive
  slug: google-drive
  status: profiled
  tags: *id021
  url: /providers/google-drive/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id022
  name: Hyland
  slug: hyland
  status: queued for profiling
  tags: *id023
  url: null
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.9
  mcp: *id024
  name: Icertis
  slug: icertis
  status: profiled
  tags: *id025
  url: /providers/icertis/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id026
  name: Ironclad
  slug: ironclad
  status: profiled
  tags: *id027
  url: /providers/ironclad/
- agent_band: agent-aware
  agent_readiness: 14.8
  band: developing
  in_catalog: true
  kin_score: 48.3
  mcp: *id028
  name: Laser Fiche
  slug: laserfiche
  status: profiled
  tags: *id029
  url: /providers/laserfiche/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id030
  name: M-Files
  slug: m-files
  status: profiled
  tags: *id031
  url: /providers/m-files/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: developing
  in_catalog: true
  kin_score: 43.4
  mcp: *id032
  name: Make
  slug: make
  status: profiled
  tags: *id033
  url: /providers/make/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id034
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id035
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id036
  name: Microsoft Dynamics 365
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id037
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id038
  name: Microsoft OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id039
  url: /providers/microsoft-onedrive/
- agent_band: agent-ready
  agent_readiness: 32.3
  band: strong
  in_catalog: true
  kin_score: 60.9
  mcp: *id040
  name: Microsoft SharePoint
  slug: sharepoint
  status: profiled
  tags: *id041
  url: /providers/sharepoint/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 19.9
  mcp: *id042
  name: Nintex Workflow Cloud
  slug: nintex
  status: profiled
  tags: *id043
  url: /providers/nintex/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id044
  name: Okta
  slug: okta
  status: profiled
  tags: *id045
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 29.5
  band: thin
  in_catalog: true
  kin_score: 28.9
  mcp: *id046
  name: ProcessMaker
  slug: processmaker
  status: profiled
  tags: *id047
  url: /providers/processmaker/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id048
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id049
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 37.0
  band: developing
  in_catalog: true
  kin_score: 45.7
  mcp: *id050
  name: SAP Ariba
  slug: ariba
  status: profiled
  tags: *id051
  url: /providers/ariba/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id052
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id053
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 34.5
  band: exemplar
  in_catalog: true
  kin_score: 71.0
  mcp: *id054
  name: UiPath
  slug: uipath
  status: profiled
  tags: *id055
  url: /providers/uipath/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id056
  name: Workday
  slug: workday
  status: profiled
  tags: *id057
  url: /providers/workday/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id058
  name: Xero
  slug: xero
  status: profiled
  tags: *id059
  url: /providers/xero/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 23.7
  mcp: *id060
  name: Zoho Docs
  slug: zoho-workdrive
  status: profiled
  tags: *id061
  url: /providers/zoho-workdrive/
siblings:
- name: Docspell
  rows: 0
  url: /applications/document-management/docspell/
- name: Mayan EDMS
  rows: 1
  url: /applications/document-management/mayan-edms/
- name: paperless-gpt
  rows: 14
  url: /applications/document-management/paperless-gpt/
- name: Paperless-ngx
  rows: 8
  url: /applications/document-management/paperless-ngx/
- name: Papra
  rows: 7
  url: /applications/document-management/papra/
- name: Stirling-PDF
  rows: 5
  url: /applications/document-management/stirling-pdf/
sitemap: true
title: 'Adobe Acrobat: Document Management & OCR reference app'
---
