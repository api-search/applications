---
app: Spendflo
app_slug: spendflo
app_url: https://www.spendflo.com/
author: API Evangelist
capabilities:
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: domain
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  - Google Workspace
  - Microsoft 365
  - OneDrive
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-150.10
  key: contract-management
  layer: domain
  name: Contract Management
  providers:
  - Adobe Sign
  - DocuSign
  - Ironclad
  - LinkSquares
  - SpotDraft
  url: /capabilities/contract-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Oracle NetSuite
  - Sage
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - BambooHR
  - HiBob
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.30
  key: it-service-management
  layer: domain
  name: IT Service Management
  providers:
  - Freshservice
  - Jira
  - ServiceNow
  url: /capabilities/it-service-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-600.70
  key: it-vendor-management
  layer: domain
  name: IT Vendor Management
  providers:
  - Airtable
  - Box
  - Browserstack
  - Canva
  - ClickUp
  - Confluence
  - Datadog
  - Figma
  - GitHub
  - HubSpot
  - Looker
  - Monday
  - PagerDuty
  - Salesforce
  - Tableau
  - Trello
  - Typeform
  - Zoom
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
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: Turbo EA
  id: BC-500
  key: procurement-management
  layer: domain
  name: Procurement Management
  providers:
  - Coupa
  url: /capabilities/procurement-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: domain
  name: Project Management
  providers:
  - Asana
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-510.30
  key: supplier-risk-management
  layer: domain
  name: Supplier Risk Management
  providers:
  - OneTrust
  - Vanta
  url: /capabilities/supplier-risk-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Google SSO
  - JumpCloud
  - Microsoft Azure AD
  - Okta
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: procurement-spend
  name: Procurement & Spend Management
  url: /applications/procurement-spend/
counts:
  declared: 46
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.spendflo.com/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-150.10
    key: contract-management
    name: Contract Management
    url: /capabilities/contract-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 34.4
    mcp: &id001
      status: none
    slug: adobe-sign
    status: profiled
    tags: &id002
    - Adobe
    - Digital Signature
    - Document Workflow
    - E-Signature
    url: /providers/adobe-sign/
  layer: domain
  name: Adobe Sign
  provider: adobe-sign
  says: lists Adobe Sign as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 52.3
    band: exemplar
    in_catalog: true
    kin_score: 68.2
    mcp: &id003
      source: https://github.com/Airtable/airtable-mcp-cli
      status: verified
    slug: airtable
    status: profiled
    tags: &id004
    - Application
    - Collaboration
    - Data
    - Database
    url: /providers/airtable/
  layer: domain
  name: Airtable
  provider: airtable
  says: lists Airtable as an integration
  source: https://www.spendflo.com/integrations
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
    agent_band: agent-ready
    agent_readiness: 55.3
    band: exemplar
    in_catalog: true
    kin_score: 72.5
    mcp: &id005
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id006
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: domain
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id007
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id008
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
  layer: domain
  name: BambooHR
  provider: bamboohr
  says: lists BambooHR as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 56.6
    band: strong
    in_catalog: true
    kin_score: 63.0
    mcp: &id009
      source: https://developer.box.com/guides/box-mcp/
      status: verified
    slug: box
    status: profiled
    tags: &id010
    - Cloud Storage
    - Collaboration
    - Content Management
    - Documents
    url: /providers/box/
  layer: domain
  name: Box
  provider: box
  says: lists Box as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 42.8
    band: exemplar
    in_catalog: true
    kin_score: 68.1
    mcp: &id011
      source: https://github.com/browserstack/mcp-server
      status: verified
    slug: browserstack
    status: profiled
    tags: &id012
    - Accessibility
    - Appium
    - Application
    - Automation
    url: /providers/browserstack/
  layer: domain
  name: Browserstack
  provider: browserstack
  says: lists Browserstack as an integration
  source: https://www.spendflo.com/integrations
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
    agent_band: agent-native
    agent_readiness: 70.0
    band: exemplar
    in_catalog: true
    kin_score: 87.3
    mcp: &id013
      source: https://www.canva.dev/docs/mcp/
      status: verified
    slug: canva
    status: profiled
    tags: &id014
    - Application
    - Automation
    - Brand Management
    - Collaboration
    url: /providers/canva/
  layer: domain
  name: Canva
  provider: canva
  says: lists Canva as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 72.6
    mcp: &id015
      source: https://developer.clickup.com/docs/connect-an-ai-assistant-to-clickups-mcp-server
      status: verified
    slug: clickup
    status: profiled
    tags: &id016
    - Collaboration
    - Productivity
    - Project Management
    - Work Management
    url: /providers/clickup/
  layer: domain
  name: ClickUp
  provider: clickup
  says: lists ClickUp as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 55.8
    band: exemplar
    in_catalog: true
    kin_score: 77.7
    mcp: &id017
      source: https://github.com/atlassian/atlassian-mcp-server
      status: verified
    slug: confluence
    status: profiled
    tags: &id018
    - Collaboration
    - Content Management
    - Documentation
    - Knowledge Base
    url: /providers/confluence/
  layer: domain
  name: Confluence
  provider: confluence
  says: lists Confluence as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 37.7
    band: developing
    in_catalog: true
    kin_score: 52.6
    mcp: &id019
      status: none
    slug: coupa
    status: profiled
    tags: &id020
    - BSM
    - Business Spend Management
    - Cloud Platform
    - Enterprise
    url: /providers/coupa/
  layer: domain
  name: Coupa
  provider: coupa
  says: lists Coupa as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 48.6
    band: exemplar
    in_catalog: true
    kin_score: 80.0
    mcp: &id021
      source: https://github.com/datadog-labs/mcp-server
      status: verified
    slug: datadog
    status: profiled
    tags: &id022
    - Analytics
    - Dashboards
    - Datadog
    - Visualization
    url: /providers/datadog/
  layer: domain
  name: Datadog
  provider: datadog
  says: lists Datadog as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id023
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id024
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
  layer: domain
  name: DocuSign
  provider: docusign
  says: lists DocuSign as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id025
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id026
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: domain
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 59.2
    band: exemplar
    in_catalog: true
    kin_score: 75.1
    mcp: &id027
      source: https://help.figma.com/hc/en-us/articles/32132100833559-Guide-to-the-Figma-MCP-server
      status: verified
    slug: figma
    status: profiled
    tags: &id028
    - Collaboration
    - Design
    - Graphics
    - Interfaces
    url: /providers/figma/
  layer: domain
  name: Figma
  provider: figma
  says: lists Figma as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 43.4
    band: thin
    in_catalog: true
    kin_score: 35.8
    mcp: &id029
      status: none
    slug: freshservice
    status: profiled
    tags: &id030
    - Asset Management
    - Help Desk
    - ITSM
    - Ticketing
    url: /providers/freshservice/
  layer: domain
  name: Freshservice
  provider: freshservice
  says: lists Freshservice as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 62.4
    band: exemplar
    in_catalog: true
    kin_score: 85.0
    mcp: &id031
      source: https://github.com/github/github-mcp-server
      status: verified
    slug: github
    status: profiled
    tags: &id032
    - Code
    - Developer Tools
    - Pipelines
    - Platform
    url: /providers/github/
  layer: domain
  name: GitHub
  provider: github
  says: lists GitHub as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id033
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id034
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 33.7
    band: strong
    in_catalog: true
    kin_score: 58.8
    mcp: &id035
      status: none
    slug: google-identity-platform
    status: profiled
    tags: &id036
    - Authentication
    - Google Cloud
    - Identity
    - Multi-Tenancy
    url: /providers/google-identity-platform/
  layer: domain
  name: Google SSO
  provider: google-identity-platform
  says: lists Google SSO as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id037
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id038
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: domain
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 19.3
    band: thin
    in_catalog: true
    kin_score: 29.3
    mcp: &id039
      source: https://apidocs.hibob.com/docs/hibob-mcp-server
      status: verified
    slug: bob
    status: profiled
    tags: &id040
    - Employee Management
    - HRIS
    - Human Resources
    - Time Off
    url: /providers/bob/
  layer: domain
  name: HiBob
  provider: bob
  says: lists HiBob as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 52.0
    band: exemplar
    in_catalog: true
    kin_score: 91.9
    mcp: &id041
      source: https://developers.hubspot.com/mcp
      status: verified
    slug: hubspot
    status: profiled
    tags: &id042
    - Analytics
    - CRM
    - Commerce
    - Content
    url: /providers/hubspot/
  layer: domain
  name: HubSpot
  provider: hubspot
  says: lists HubSpot as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id043
      status: none
    slug: ironclad
    status: profiled
    tags: &id044
    - Contract Lifecycle Management
    - Contracts
    - Legal Tech
    - LegalOps
    url: /providers/ironclad/
  layer: domain
  name: Ironclad
  provider: ironclad
  says: lists Ironclad as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id045
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id046
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: domain
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id047
      source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
      status: verified
    slug: jumpcloud
    status: profiled
    tags: &id048
    - Directory Services
    - Identity
    - MFA
    - SSO
    url: /providers/jumpcloud/
  layer: domain
  name: JumpCloud
  provider: jumpcloud
  says: lists JumpCloud as an integration
  source: https://www.spendflo.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 26.6
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id049
      source: https://linksquares.com/inhouse-insights/mcp-connector-anthropic-claude/
      status: verified
    slug: linksquares
    status: profiled
    tags: &id050
    - Artificial Intelligence
    - Contract Lifecycle Management
    - Contract Management
    - Contracts
    url: /providers/linksquares/
  layer: domain
  name: LinkSquares
  provider: linksquares
  says: lists LinkSquares as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 33.6
    band: strong
    in_catalog: true
    kin_score: 58.1
    mcp: &id051
      source: https://docs.cloud.google.com/looker/docs/mcp
      status: verified
    slug: looker
    status: profiled
    tags: &id052
    - Analytics
    - BI Platform
    - Business Intelligence
    - Data Analytics
    url: /providers/looker/
  layer: domain
  name: Looker
  provider: looker
  says: lists Looker as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id053
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-365
    status: profiled
    tags: &id054
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/microsoft-365/
  layer: domain
  name: Microsoft 365
  provider: microsoft-365
  says: lists Microsoft 365 as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 28.7
    band: exemplar
    in_catalog: true
    kin_score: 70.3
    mcp: &id055
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id056
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Azure AD
  provider: microsoft-entra
  says: lists Microsoft Azure AD as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 50.3
    band: thin
    in_catalog: true
    kin_score: 32.2
    mcp: &id057
      source: https://github.com/mondaycom/mcp
      status: verified
    slug: monday-com
    status: profiled
    tags: &id058
    - Automation
    - CRM
    - GraphQL
    - Work Management
    url: /providers/monday-com/
  layer: domain
  name: Monday
  provider: monday-com
  says: lists Monday as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id059
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id060
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: domain
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id061
      status: none
    slug: microsoft-onedrive
    status: profiled
    tags: &id062
    - Cloud Storage
    - File
    - File Storage
    - Microsoft
    url: /providers/microsoft-onedrive/
  layer: domain
  name: OneDrive
  provider: microsoft-onedrive
  says: lists OneDrive as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id063
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id064
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: domain
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://www.spendflo.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-510.30
    key: supplier-risk-management
    name: Supplier Risk Management
    url: /capabilities/supplier-risk-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 57.2
    band: exemplar
    in_catalog: true
    kin_score: 78.3
    mcp: &id065
      status: none
    slug: onetrust
    status: profiled
    tags: &id066
    - Compliance
    - Consent
    - GRC
    - Privacy
    url: /providers/onetrust/
  layer: domain
  name: OneTrust
  provider: onetrust
  says: lists OneTrust as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id067
      status: none
    slug: netsuite
    status: profiled
    tags: &id068
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: Oracle NetSuite
  provider: netsuite
  says: lists Oracle NetSuite as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 54.4
    band: developing
    in_catalog: true
    kin_score: 52.1
    mcp: &id069
      source: https://github.com/PagerDuty/pagerduty-mcp-server
      status: verified
    slug: pagerduty
    status: profiled
    tags: &id070
    - Alerting
    - DevOps
    - Incident Management
    - On-Call Management
    url: /providers/pagerduty/
  layer: domain
  name: PagerDuty
  provider: pagerduty
  says: lists PagerDuty as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id071
      status: none
    slug: sage
    status: profiled
    tags: &id072
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: domain
  name: Sage
  provider: sage
  says: lists Sage as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 53.6
    band: exemplar
    in_catalog: true
    kin_score: 88.0
    mcp: &id073
      source: https://github.com/salesforcecli/mcp
      status: verified
    slug: salesforce
    status: profiled
    tags: &id074
    - Analytics
    - Artificial Intelligence
    - Cloud
    - Fortune 500
    url: /providers/salesforce/
  layer: domain
  name: Salesforce
  provider: salesforce
  says: lists Salesforce as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id075
      status: none
    slug: servicenow
    status: profiled
    tags: &id076
    - Automation
    - Cloud Services
    - Digital Workflows
    - ServiceNow
    url: /providers/servicenow/
  layer: domain
  name: ServiceNow
  provider: servicenow
  says: lists ServiceNow as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id077
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id078
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: domain
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.spendflo.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 28.4
    band: developing
    in_catalog: true
    kin_score: 44.4
    mcp: &id079
      status: unknown
    slug: spotdraft
    status: profiled
    tags: &id080
    - Contract Lifecycle Management
    - Contracts
    - E-Signature
    - Legal Tech
    url: /providers/spotdraft/
  layer: domain
  name: SpotDraft
  provider: spotdraft
  says: lists SpotDraft as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 55.0
    band: developing
    in_catalog: true
    kin_score: 49.9
    mcp: &id081
      source: https://github.com/tableau/tableau-mcp
      status: verified
    slug: tableau
    status: profiled
    tags: &id082
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Visualization
    url: /providers/tableau/
  layer: domain
  name: Tableau
  provider: tableau
  says: lists Tableau as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 30.8
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id083
      source: https://github.com/atlassian/trello-mcp-server
      status: verified
    slug: trello
    status: profiled
    tags: &id084
    - Collaboration
    - Kanban
    - Project Management
    - Task Management
    url: /providers/trello/
  layer: domain
  name: Trello
  provider: trello
  says: lists Trello as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 42.6
    band: thin
    in_catalog: true
    kin_score: 36.0
    mcp: &id085
      source: https://www.typeform.com/developers/mcp
      status: verified
    slug: typeform
    status: profiled
    tags: &id086
    - Forms
    - Lead Capture
    - Software-as-a-Service
    - Surveys
    url: /providers/typeform/
  layer: domain
  name: Typeform
  provider: typeform
  says: lists Typeform as an integration
  source: https://www.spendflo.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-510.30
    key: supplier-risk-management
    name: Supplier Risk Management
    url: /capabilities/supplier-risk-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 43.6
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id087
      source: https://github.com/VantaInc/vanta-mcp-server
      status: verified
    slug: vanta
    status: profiled
    tags: &id088
    - Compliance
    - Cybersecurity
    - Governance
    - Security
    url: /providers/vanta/
  layer: domain
  name: Vanta
  provider: vanta
  says: lists Vanta as an integration
  source: https://www.spendflo.com/integrations
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
    mcp: &id089
      status: none
    slug: workday
    status: profiled
    tags: &id090
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.spendflo.com/integrations
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
    agent_readiness: 56.8
    band: strong
    in_catalog: true
    kin_score: 57.1
    mcp: &id091
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id092
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: domain
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.spendflo.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/procurement-spend/spendflo/
providers:
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 34.4
  mcp: *id001
  name: Adobe Sign
  slug: adobe-sign
  status: profiled
  tags: *id002
  url: /providers/adobe-sign/
- agent_band: agent-ready
  agent_readiness: 52.3
  band: exemplar
  in_catalog: true
  kin_score: 68.2
  mcp: *id003
  name: Airtable
  slug: airtable
  status: profiled
  tags: *id004
  url: /providers/airtable/
- agent_band: agent-ready
  agent_readiness: 55.3
  band: exemplar
  in_catalog: true
  kin_score: 72.5
  mcp: *id005
  name: Asana
  slug: asana
  status: profiled
  tags: *id006
  url: /providers/asana/
- agent_band: agent-aware
  agent_readiness: 26.3
  band: developing
  in_catalog: true
  kin_score: 40.7
  mcp: *id007
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id008
  url: /providers/bamboohr/
- agent_band: agent-ready
  agent_readiness: 56.6
  band: strong
  in_catalog: true
  kin_score: 63.0
  mcp: *id009
  name: Box
  slug: box
  status: profiled
  tags: *id010
  url: /providers/box/
- agent_band: agent-ready
  agent_readiness: 42.8
  band: exemplar
  in_catalog: true
  kin_score: 68.1
  mcp: *id011
  name: Browserstack
  slug: browserstack
  status: profiled
  tags: *id012
  url: /providers/browserstack/
- agent_band: agent-native
  agent_readiness: 70.0
  band: exemplar
  in_catalog: true
  kin_score: 87.3
  mcp: *id013
  name: Canva
  slug: canva
  status: profiled
  tags: *id014
  url: /providers/canva/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 72.6
  mcp: *id015
  name: ClickUp
  slug: clickup
  status: profiled
  tags: *id016
  url: /providers/clickup/
- agent_band: agent-ready
  agent_readiness: 55.8
  band: exemplar
  in_catalog: true
  kin_score: 77.7
  mcp: *id017
  name: Confluence
  slug: confluence
  status: profiled
  tags: *id018
  url: /providers/confluence/
- agent_band: agent-ready
  agent_readiness: 37.7
  band: developing
  in_catalog: true
  kin_score: 52.6
  mcp: *id019
  name: Coupa
  slug: coupa
  status: profiled
  tags: *id020
  url: /providers/coupa/
- agent_band: agent-ready
  agent_readiness: 48.6
  band: exemplar
  in_catalog: true
  kin_score: 80.0
  mcp: *id021
  name: Datadog
  slug: datadog
  status: profiled
  tags: *id022
  url: /providers/datadog/
- agent_band: agent-ready
  agent_readiness: 34.7
  band: exemplar
  in_catalog: true
  kin_score: 71.5
  mcp: *id023
  name: DocuSign
  slug: docusign
  status: profiled
  tags: *id024
  url: /providers/docusign/
- agent_band: agent-ready
  agent_readiness: 44.8
  band: developing
  in_catalog: true
  kin_score: 45.9
  mcp: *id025
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id026
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 59.2
  band: exemplar
  in_catalog: true
  kin_score: 75.1
  mcp: *id027
  name: Figma
  slug: figma
  status: profiled
  tags: *id028
  url: /providers/figma/
- agent_band: agent-ready
  agent_readiness: 43.4
  band: thin
  in_catalog: true
  kin_score: 35.8
  mcp: *id029
  name: Freshservice
  slug: freshservice
  status: profiled
  tags: *id030
  url: /providers/freshservice/
- agent_band: agent-ready
  agent_readiness: 62.4
  band: exemplar
  in_catalog: true
  kin_score: 85.0
  mcp: *id031
  name: GitHub
  slug: github
  status: profiled
  tags: *id032
  url: /providers/github/
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id033
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id034
  url: /providers/google-gmail/
- agent_band: agent-ready
  agent_readiness: 33.7
  band: strong
  in_catalog: true
  kin_score: 58.8
  mcp: *id035
  name: Google SSO
  slug: google-identity-platform
  status: profiled
  tags: *id036
  url: /providers/google-identity-platform/
- agent_band: agent-ready
  agent_readiness: 43.0
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id037
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id038
  url: /providers/google-workspace/
- agent_band: agent-aware
  agent_readiness: 19.3
  band: thin
  in_catalog: true
  kin_score: 29.3
  mcp: *id039
  name: HiBob
  slug: bob
  status: profiled
  tags: *id040
  url: /providers/bob/
- agent_band: agent-ready
  agent_readiness: 52.0
  band: exemplar
  in_catalog: true
  kin_score: 91.9
  mcp: *id041
  name: HubSpot
  slug: hubspot
  status: profiled
  tags: *id042
  url: /providers/hubspot/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: developing
  in_catalog: true
  kin_score: 52.3
  mcp: *id043
  name: Ironclad
  slug: ironclad
  status: profiled
  tags: *id044
  url: /providers/ironclad/
- agent_band: agent-ready
  agent_readiness: 64.4
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id045
  name: Jira
  slug: jira
  status: profiled
  tags: *id046
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: thin
  in_catalog: true
  kin_score: 33.6
  mcp: *id047
  name: JumpCloud
  slug: jumpcloud
  status: profiled
  tags: *id048
  url: /providers/jumpcloud/
- agent_band: agent-aware
  agent_readiness: 26.6
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id049
  name: LinkSquares
  slug: linksquares
  status: profiled
  tags: *id050
  url: /providers/linksquares/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: strong
  in_catalog: true
  kin_score: 58.1
  mcp: *id051
  name: Looker
  slug: looker
  status: profiled
  tags: *id052
  url: /providers/looker/
- agent_band: agent-ready
  agent_readiness: 36.3
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id053
  name: Microsoft 365
  slug: microsoft-365
  status: profiled
  tags: *id054
  url: /providers/microsoft-365/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id055
  name: Microsoft Azure AD
  slug: microsoft-entra
  status: profiled
  tags: *id056
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 50.3
  band: thin
  in_catalog: true
  kin_score: 32.2
  mcp: *id057
  name: Monday
  slug: monday-com
  status: profiled
  tags: *id058
  url: /providers/monday-com/
- agent_band: agent-ready
  agent_readiness: 47.1
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id059
  name: Okta
  slug: okta
  status: profiled
  tags: *id060
  url: /providers/okta/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: developing
  in_catalog: true
  kin_score: 50.9
  mcp: *id061
  name: OneDrive
  slug: microsoft-onedrive
  status: profiled
  tags: *id062
  url: /providers/microsoft-onedrive/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id063
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id064
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 57.2
  band: exemplar
  in_catalog: true
  kin_score: 78.3
  mcp: *id065
  name: OneTrust
  slug: onetrust
  status: profiled
  tags: *id066
  url: /providers/onetrust/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id067
  name: Oracle NetSuite
  slug: netsuite
  status: profiled
  tags: *id068
  url: /providers/netsuite/
- agent_band: agent-ready
  agent_readiness: 54.4
  band: developing
  in_catalog: true
  kin_score: 52.1
  mcp: *id069
  name: PagerDuty
  slug: pagerduty
  status: profiled
  tags: *id070
  url: /providers/pagerduty/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id071
  name: Sage
  slug: sage
  status: profiled
  tags: *id072
  url: /providers/sage/
- agent_band: agent-ready
  agent_readiness: 53.6
  band: exemplar
  in_catalog: true
  kin_score: 88.0
  mcp: *id073
  name: Salesforce
  slug: salesforce
  status: profiled
  tags: *id074
  url: /providers/salesforce/
- agent_band: agent-ready
  agent_readiness: 42.3
  band: strong
  in_catalog: true
  kin_score: 61.9
  mcp: *id075
  name: ServiceNow
  slug: servicenow
  status: profiled
  tags: *id076
  url: /providers/servicenow/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: exemplar
  in_catalog: true
  kin_score: 74.4
  mcp: *id077
  name: Slack
  slug: slack
  status: profiled
  tags: *id078
  url: /providers/slack/
- agent_band: agent-aware
  agent_readiness: 28.4
  band: developing
  in_catalog: true
  kin_score: 44.4
  mcp: *id079
  name: SpotDraft
  slug: spotdraft
  status: profiled
  tags: *id080
  url: /providers/spotdraft/
- agent_band: agent-ready
  agent_readiness: 55.0
  band: developing
  in_catalog: true
  kin_score: 49.9
  mcp: *id081
  name: Tableau
  slug: tableau
  status: profiled
  tags: *id082
  url: /providers/tableau/
- agent_band: agent-ready
  agent_readiness: 30.8
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id083
  name: Trello
  slug: trello
  status: profiled
  tags: *id084
  url: /providers/trello/
- agent_band: agent-ready
  agent_readiness: 42.6
  band: thin
  in_catalog: true
  kin_score: 36.0
  mcp: *id085
  name: Typeform
  slug: typeform
  status: profiled
  tags: *id086
  url: /providers/typeform/
- agent_band: agent-ready
  agent_readiness: 43.6
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id087
  name: Vanta
  slug: vanta
  status: profiled
  tags: *id088
  url: /providers/vanta/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 54.7
  mcp: *id089
  name: Workday
  slug: workday
  status: profiled
  tags: *id090
  url: /providers/workday/
- agent_band: agent-ready
  agent_readiness: 56.8
  band: strong
  in_catalog: true
  kin_score: 57.1
  mcp: *id091
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id092
  url: /providers/zoom/
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
- name: Tradogram
  rows: 32
  url: /applications/procurement-spend/tradogram/
- name: Vendr
  rows: 20
  url: /applications/procurement-spend/vendr/
sitemap: true
title: 'Spendflo: Procurement & Spend Management reference app'
---
