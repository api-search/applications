---
app: Tradogram
app_slug: tradogram
app_url: https://www.tradogram.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.20
  key: accounts-payable-management
  layer: domain
  name: Accounts Payable Management
  providers:
  - Bill.com
  url: /capabilities/accounts-payable-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-610.50
  key: analytics-bi-management
  layer: domain
  name: Analytics & BI Management
  providers:
  - Power BI
  url: /capabilities/analytics-bi-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Blackbaud
  - Microsoft Dynamics
  - Microsoft Dynamics 365 Business Central
  - MYOB
  - NetSuite
  - Oracle
  - QuickBooks Online / Desktop
  - Sage 50 / Sage 300
  - Sage Intacct
  - SAP
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: domain
  name: Mailbox & Calendar Sync
  providers:
  - Gmail
  - Microsoft Outlook
  url: /capabilities/mailbox-calendar-sync/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-957
  key: AE-957
  layer: domain
  name: PunchOut Catalog Commerce
  providers:
  - Amazon
  - B&H
  - Best Buy Business
  - CDW
  - DigiKey
  - Global Industrial
  - Grainger
  - McMaster-Carr
  - MSC Industrial Supply
  - Newegg Business
  - Office Depot
  - Quill
  - Staples
  - Thermo Fisher / Fisher Scientific
  - Uline
  url: /capabilities/purchase-order-management/
  via_parent: Purchase Order Management
- attribution: Turbo EA
  id: BC-4230.50
  key: tenant-identity-federation
  layer: domain
  name: Tenant Identity Federation
  providers:
  - Microsoft Azure AD
  - OneLogin
  url: /capabilities/tenant-identity-federation/
  via_parent: null
category:
  id: procurement-spend
  name: Procurement & Spend Management
  url: /applications/procurement-spend/
counts:
  declared: 32
  observed: 0
credits: []
evidence:
- route: integrations page
  url: https://www.tradogram.com/integrations
integrations:
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 26.7
    band: developing
    in_catalog: true
    kin_score: 39.8
    mcp: &id001
      source: https://docs.business.amazon.com/
      status: documented
    slug: amazon-business
    status: profiled
    tags: &id002
    - B2B
    - Company
    - Marketplace
    - Procurement
    url: /providers/amazon-business/
  layer: domain
  name: Amazon
  provider: amazon-business
  says: lists Amazon as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 0.4
    mcp: &id003
      status: unchecked
    slug: b-h-photo-video
    status: profiled
    tags: &id004
    - Company
    url: /providers/b-h-photo-video/
  layer: domain
  name: B&H
  provider: b-h-photo-video
  says: lists B&H as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.3
    band: developing
    in_catalog: true
    kin_score: 50.1
    mcp: &id005
      status: none
    slug: best-buy
    status: profiled
    tags: &id006
    - Consumer Electronics
    - E-Commerce
    - Fortune 100
    - Retail
    url: /providers/best-buy/
  layer: domain
  name: Best Buy Business
  provider: best-buy
  says: lists Best Buy Business as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.20
    key: accounts-payable-management
    name: Accounts Payable Management
    url: /capabilities/accounts-payable-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.7
    band: developing
    in_catalog: true
    kin_score: 51.7
    mcp: &id007
      source: https://developer.bill.com/docs/bill-mcp-server
      status: verified
    slug: bill
    status: profiled
    tags: &id008
    - Accounts Payable
    - Accounts Receivable
    - Expense Management
    - Spend Management
    url: /providers/bill/
  layer: domain
  name: Bill.com
  provider: bill
  says: lists Bill.com as an integration
  source: https://www.tradogram.com/integrations
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
    agent_readiness: 31.6
    band: strong
    in_catalog: true
    kin_score: 55.3
    mcp: &id009
      status: none
    slug: blackbaud
    status: profiled
    tags: &id010
    - CRM
    - Donor Management
    - Fundraising
    - Non-Profit
    url: /providers/blackbaud/
  layer: domain
  name: Blackbaud
  provider: blackbaud
  says: lists Blackbaud as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.6
    band: minimal
    in_catalog: true
    kin_score: 9.7
    mcp: &id011
      status: unknown
    slug: cdw
    status: profiled
    tags: &id012
    - B2B
    - Catalog
    - IT Distribution
    - eProcurement
    url: /providers/cdw/
  layer: domain
  name: CDW
  provider: cdw
  says: lists CDW as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 27.5
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id013
      status: none
    slug: digi-key
    status: profiled
    tags: &id014
    - Distribution
    - Electronic Components
    - Public APIs
    - Shopping
    url: /providers/digi-key/
  layer: domain
  name: DigiKey
  provider: digi-key
  says: lists DigiKey as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id015
      status: unchecked
    slug: global-industrial
    status: queued for profiling
    tags: &id016 []
    url: null
  layer: domain
  name: Global Industrial
  provider: global-industrial
  says: lists Global Industrial as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id017
      source: https://developers.google.com/workspace/gmail/api/guides/configure-mcp-server
      status: verified
    slug: google-gmail
    status: profiled
    tags: &id018
    - Drafts
    - Email
    - Gmail
    - Google
    url: /providers/google-gmail/
  layer: domain
  name: Gmail
  provider: google-gmail
  says: lists Gmail as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 7.3
    mcp: &id019
      status: unknown
    slug: ww-grainger
    status: profiled
    tags: &id020
    - Distribution
    - Fortune 500
    - Industrial Supply
    - MRO
    url: /providers/ww-grainger/
  layer: domain
  name: Grainger
  provider: ww-grainger
  says: lists Grainger as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: emerging
    in_catalog: true
    kin_score: 16.4
    mcp: &id021
      status: unchecked
    slug: mcmaster-carr
    status: profiled
    tags: &id022
    - Catalog
    - Company
    - Industrial
    - Supplies
    url: /providers/mcmaster-carr/
  layer: domain
  name: McMaster-Carr
  provider: mcmaster-carr
  says: lists McMaster-Carr as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id023
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id024
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: domain
  name: Microsoft Azure AD
  provider: microsoft-entra
  says: lists Microsoft Azure AD as an integration
  source: https://www.tradogram.com/integrations
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
    agent_readiness: 37.6
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id025
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id026
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics as an integration
  source: https://www.tradogram.com/integrations
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
    agent_readiness: 39.9
    band: exemplar
    in_catalog: true
    kin_score: 73.1
    mcp: &id027
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id028
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: domain
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id029
      source: https://github.com/microsoft/mcp
      status: verified
    slug: microsoft-outlook
    status: profiled
    tags: &id030
    - Calendar
    - Contacts
    - Email
    - Enterprise
    url: /providers/microsoft-outlook/
  layer: domain
  name: Microsoft Outlook
  provider: microsoft-outlook
  says: lists Microsoft Outlook as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: msc-industrial-supply
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: domain
  name: MSC Industrial Supply
  provider: msc-industrial-supply
  says: lists MSC Industrial Supply as an integration
  source: https://www.tradogram.com/integrations
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
    band: emerging
    in_catalog: true
    kin_score: 22.5
    mcp: &id033
      status: none
    slug: myob
    status: profiled
    tags: &id034
    - Accounting
    - Bills
    - Business Management
    - Invoices
    url: /providers/myob/
  layer: domain
  name: MYOB
  provider: myob
  says: lists MYOB as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id035
      status: none
    slug: netsuite
    status: profiled
    tags: &id036
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: NetSuite
  provider: netsuite
  says: lists NetSuite as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: thin
    in_catalog: true
    kin_score: 29.5
    mcp: &id037
      status: none
    slug: newegg
    status: profiled
    tags: &id038
    - Company
    - Consumer
    - E-Commerce
    - Marketplace
    url: /providers/newegg/
  layer: domain
  name: Newegg Business
  provider: newegg
  says: lists Newegg Business as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 2.1
    mcp: &id039
      status: none
    slug: office-depot
    status: profiled
    tags: &id040
    - B2B
    - Fortune 500
    - Office Supplies
    - Retail
    url: /providers/office-depot/
  layer: domain
  name: Office Depot
  provider: office-depot
  says: lists Office Depot as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id041
      source: https://github.com/onelogin/onelogin-mcp
      status: verified
    slug: onelogin
    status: profiled
    tags: &id042
    - Identity
    - Identity and Access Management
    - Multi-Factor Authentication
    - SSO
    url: /providers/onelogin/
  layer: domain
  name: OneLogin
  provider: onelogin
  says: lists OneLogin as an integration
  source: https://www.tradogram.com/integrations
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
    agent_readiness: 59.8
    band: exemplar
    in_catalog: true
    kin_score: 70.4
    mcp: &id043
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id044
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle
  provider: oracle
  says: lists Oracle as an integration
  source: https://www.tradogram.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 28.3
    band: exemplar
    in_catalog: true
    kin_score: 76.0
    mcp: &id045
      source: https://github.com/microsoft/powerbi-modeling-mcp
      status: verified
    slug: power-bi
    status: profiled
    tags: &id046
    - Analytics
    - Business Intelligence
    - Dashboards
    - Data Analysis
    url: /providers/power-bi/
  layer: domain
  name: Power BI
  provider: power-bi
  says: lists Power BI as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id047
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id048
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online / Desktop
  provider: quickbooks
  says: lists QuickBooks Online / Desktop as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 8.2
    mcp: &id049
      status: unchecked
    slug: quill-com
    status: profiled
    tags: &id050
    - B2B
    - Company
    - E-Commerce
    - Office Supplies
    url: /providers/quill-com/
  layer: domain
  name: Quill
  provider: quill-com
  says: lists Quill as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id051
      status: none
    slug: sage
    status: profiled
    tags: &id052
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: domain
  name: Sage 50 / Sage 300
  provider: sage
  says: lists Sage 50 / Sage 300 as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id053
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id054
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.tradogram.com/integrations
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
    agent_readiness: 58.7
    band: strong
    in_catalog: true
    kin_score: 58.3
    mcp: &id055
      source: https://github.com/SAP/mdk-mcp-server
      status: verified
    slug: sap
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - BTP
    - Business Applications
    - SAP
    url: /providers/sap/
  layer: domain
  name: SAP
  provider: sap
  says: lists SAP as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.2
    band: thin
    in_catalog: true
    kin_score: 30.6
    mcp: &id057
      status: none
    slug: staples
    status: profiled
    tags: &id058
    - B2B
    - Office Supplies
    - Procurement
    - Retail
    url: /providers/staples/
  layer: domain
  name: Staples
  provider: staples
  says: lists Staples as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 20.3
    band: thin
    in_catalog: true
    kin_score: 26.4
    mcp: &id059
      status: unknown
    slug: thermo-fisher-scientific
    status: profiled
    tags: &id060
    - LIMS
    - Laboratory
    - Life Sciences
    - Scientific Instruments
    url: /providers/thermo-fisher-scientific/
  layer: domain
  name: Thermo Fisher / Fisher Scientific
  provider: thermo-fisher-scientific
  says: lists Thermo Fisher / Fisher Scientific as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-957
    key: AE-957
    name: PunchOut Catalog Commerce
    url: /capabilities/purchase-order-management/
    via_parent: Purchase Order Management
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 3.0
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id061
      status: unchecked
    slug: uline
    status: profiled
    tags: &id062
    - Company
    - Industrial Supplies
    - Packaging
    - Shipping
    url: /providers/uline/
  layer: domain
  name: Uline
  provider: uline
  says: lists Uline as an integration
  source: https://www.tradogram.com/integrations
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
    mcp: &id063
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id064
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.tradogram.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/procurement-spend/tradogram/
providers:
- agent_band: agent-aware
  agent_readiness: 26.7
  band: developing
  in_catalog: true
  kin_score: 39.8
  mcp: *id001
  name: Amazon
  slug: amazon-business
  status: profiled
  tags: *id002
  url: /providers/amazon-business/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 0.4
  mcp: *id003
  name: B&H
  slug: b-h-photo-video
  status: profiled
  tags: *id004
  url: /providers/b-h-photo-video/
- agent_band: agent-ready
  agent_readiness: 30.3
  band: developing
  in_catalog: true
  kin_score: 50.1
  mcp: *id005
  name: Best Buy Business
  slug: best-buy
  status: profiled
  tags: *id006
  url: /providers/best-buy/
- agent_band: agent-ready
  agent_readiness: 29.7
  band: developing
  in_catalog: true
  kin_score: 51.7
  mcp: *id007
  name: Bill.com
  slug: bill
  status: profiled
  tags: *id008
  url: /providers/bill/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: strong
  in_catalog: true
  kin_score: 55.3
  mcp: *id009
  name: Blackbaud
  slug: blackbaud
  status: profiled
  tags: *id010
  url: /providers/blackbaud/
- agent_band: human-only
  agent_readiness: 0.6
  band: minimal
  in_catalog: true
  kin_score: 9.7
  mcp: *id011
  name: CDW
  slug: cdw
  status: profiled
  tags: *id012
  url: /providers/cdw/
- agent_band: agent-aware
  agent_readiness: 27.5
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id013
  name: DigiKey
  slug: digi-key
  status: profiled
  tags: *id014
  url: /providers/digi-key/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id015
  name: Global Industrial
  slug: global-industrial
  status: queued for profiling
  tags: *id016
  url: null
- agent_band: agent-ready
  agent_readiness: 43.2
  band: exemplar
  in_catalog: true
  kin_score: 66.8
  mcp: *id017
  name: Gmail
  slug: google-gmail
  status: profiled
  tags: *id018
  url: /providers/google-gmail/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 7.3
  mcp: *id019
  name: Grainger
  slug: ww-grainger
  status: profiled
  tags: *id020
  url: /providers/ww-grainger/
- agent_band: human-only
  agent_readiness: 3.0
  band: emerging
  in_catalog: true
  kin_score: 16.4
  mcp: *id021
  name: McMaster-Carr
  slug: mcmaster-carr
  status: profiled
  tags: *id022
  url: /providers/mcmaster-carr/
- agent_band: agent-ready
  agent_readiness: 28.7
  band: exemplar
  in_catalog: true
  kin_score: 70.3
  mcp: *id023
  name: Microsoft Azure AD
  slug: microsoft-entra
  status: profiled
  tags: *id024
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 37.6
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id025
  name: Microsoft Dynamics
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id026
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 39.9
  band: exemplar
  in_catalog: true
  kin_score: 73.1
  mcp: *id027
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id028
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: agent-ready
  agent_readiness: 42.9
  band: exemplar
  in_catalog: true
  kin_score: 70.8
  mcp: *id029
  name: Microsoft Outlook
  slug: microsoft-outlook
  status: profiled
  tags: *id030
  url: /providers/microsoft-outlook/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: MSC Industrial Supply
  slug: msc-industrial-supply
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 22.5
  mcp: *id033
  name: MYOB
  slug: myob
  status: profiled
  tags: *id034
  url: /providers/myob/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 11.4
  mcp: *id035
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id036
  url: /providers/netsuite/
- agent_band: human-only
  agent_readiness: 2.5
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id037
  name: Newegg Business
  slug: newegg
  status: profiled
  tags: *id038
  url: /providers/newegg/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 2.1
  mcp: *id039
  name: Office Depot
  slug: office-depot
  status: profiled
  tags: *id040
  url: /providers/office-depot/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: thin
  in_catalog: true
  kin_score: 29.5
  mcp: *id041
  name: OneLogin
  slug: onelogin
  status: profiled
  tags: *id042
  url: /providers/onelogin/
- agent_band: agent-ready
  agent_readiness: 59.8
  band: exemplar
  in_catalog: true
  kin_score: 70.4
  mcp: *id043
  name: Oracle
  slug: oracle
  status: profiled
  tags: *id044
  url: /providers/oracle/
- agent_band: agent-aware
  agent_readiness: 28.3
  band: exemplar
  in_catalog: true
  kin_score: 76.0
  mcp: *id045
  name: Power BI
  slug: power-bi
  status: profiled
  tags: *id046
  url: /providers/power-bi/
- agent_band: agent-ready
  agent_readiness: 38.3
  band: strong
  in_catalog: true
  kin_score: 59.8
  mcp: *id047
  name: QuickBooks Online / Desktop
  slug: quickbooks
  status: profiled
  tags: *id048
  url: /providers/quickbooks/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id049
  name: Quill
  slug: quill-com
  status: profiled
  tags: *id050
  url: /providers/quill-com/
- agent_band: agent-ready
  agent_readiness: 30.6
  band: developing
  in_catalog: true
  kin_score: 41.7
  mcp: *id051
  name: Sage 50 / Sage 300
  slug: sage
  status: profiled
  tags: *id052
  url: /providers/sage/
- agent_band: agent-aware
  agent_readiness: 15.1
  band: thin
  in_catalog: true
  kin_score: 26.5
  mcp: *id053
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id054
  url: /providers/sage-intacct/
- agent_band: agent-ready
  agent_readiness: 58.7
  band: strong
  in_catalog: true
  kin_score: 58.3
  mcp: *id055
  name: SAP
  slug: sap
  status: profiled
  tags: *id056
  url: /providers/sap/
- agent_band: agent-aware
  agent_readiness: 19.2
  band: thin
  in_catalog: true
  kin_score: 30.6
  mcp: *id057
  name: Staples
  slug: staples
  status: profiled
  tags: *id058
  url: /providers/staples/
- agent_band: agent-aware
  agent_readiness: 20.3
  band: thin
  in_catalog: true
  kin_score: 26.4
  mcp: *id059
  name: Thermo Fisher / Fisher Scientific
  slug: thermo-fisher-scientific
  status: profiled
  tags: *id060
  url: /providers/thermo-fisher-scientific/
- agent_band: human-only
  agent_readiness: 3.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id061
  name: Uline
  slug: uline
  status: profiled
  tags: *id062
  url: /providers/uline/
- agent_band: agent-native
  agent_readiness: 60.0
  band: exemplar
  in_catalog: true
  kin_score: 87.1
  mcp: *id063
  name: Xero
  slug: xero
  status: profiled
  tags: *id064
  url: /providers/xero/
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
- name: Vendr
  rows: 20
  url: /applications/procurement-spend/vendr/
sitemap: true
title: 'Tradogram: Procurement & Spend Management reference app'
---
