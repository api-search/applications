---
app: Ramp
app_slug: ramp
app_url: https://ramp.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-210.10
  key: cash-management
  layer: domain
  name: Cash Management
  providers:
  - Ally Bank
  - Alpine Bank
  - Bank of America
  - Mercury
  - TD Bank
  - US Bank
  - Wells Fargo
  url: /capabilities/cash-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.10
  key: AE-210.10
  layer: domain
  name: Flight Search & Booking
  providers:
  - American Airlines AAdvantage Business
  url: /capabilities/flight-search-booking/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-140.100.20
  key: AE-140.100.20
  layer: domain
  name: Food Delivery
  providers:
  - DoorDash
  url: /capabilities/quick-local-commerce/
  via_parent: Quick & Local Commerce
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Acumatica
  - Aplos
  - Blackbaud
  - Campfire
  - Deltek Vantagepoint
  - Digits
  - DualEntry
  - Finaloop
  - Microsoft Dynamics 365 Business Central
  - Microsoft Dynamics 365 Finance and Operations
  - NetSuite
  - Odoo
  - Oracle Fusion Cloud
  - Puzzle
  - QuickBooks Online / Desktop
  - Rillet
  - Sage 100 / Sage 300
  - Sage Intacct
  - Viewpoint Spectrum / Vista
  - Workday Financial Management
  - Xero
  - Yardi
  - Zoho Books
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - ADP
  - BambooHR
  - Gusto
  - Justworks
  - Paychex
  - Paylocity
  - SAP SuccessFactors
  - Square Payroll
  - TriNet
  - UKG Pro / UKG Ready
  - Workday
  - Zenefits
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-500
  key: procurement-management
  layer: domain
  name: Procurement Management
  providers:
  - Amazon Business
  - CloudEagle
  url: /capabilities/procurement-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.30.10
  key: AE-210.30.10
  layer: domain
  name: Ride Hailing
  providers:
  - Lyft
  - Uber
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: API Evangelist extension
  id: AE-916
  key: AE-916
  layer: common
  name: Cloud Drive & File Sync
  providers:
  - Dropbox
  url: /capabilities/it-infrastructure-management/
  via_parent: IT Infrastructure Management
- attribution: Turbo EA
  id: BC-150.10
  key: contract-management
  layer: common
  name: Contract Management
  providers:
  - Docusign
  - Ironclad
  url: /capabilities/contract-management/
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
  - Microsoft Teams
  - Slack
  url: /capabilities/internal-communications-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.80
  key: AE-150.80
  layer: common
  name: Mailbox & Calendar Sync
  providers:
  - Google Calendar
  url: /capabilities/mailbox-calendar-sync/
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
  id: BC-4220.20
  key: observability-management
  layer: common
  name: Observability Management
  providers:
  - Sentry
  url: /capabilities/observability-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4280.30
  key: product-usage-analytics
  layer: common
  name: Product Usage Analytics
  providers:
  - Segment
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-900.30
  key: project-management
  layer: common
  name: Project Management
  providers:
  - Asana
  - Jira
  - Linear
  url: /capabilities/project-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4290
  key: saas-trust-service-compliance-management
  layer: common
  name: SaaS Trust & Service Compliance Management
  providers:
  - Drata
  url: /capabilities/saas-trust-service-compliance-management/
  via_parent: null
category:
  id: expense-management
  name: Expense & Spend Management
  url: /applications/expense-management/
counts:
  declared: 59
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
- route: integrations page
  url: https://ramp.com/integrations
integrations:
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
    agent_readiness: 24.7
    band: emerging
    in_catalog: true
    kin_score: 23.0
    mcp: &id024
      status: none
    slug: branch-io
    status: profiled
    tags: &id025
    - Company
    url: /providers/branch-io/
  layer: common
  name: Branch
  provider: branch-io
  says: ships the Branch SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
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
    agent_band: agent-aware
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 43.8
    mcp: &id092
      status: none
    slug: segment
    status: profiled
    tags: &id093
    - CDP
    - Company
    - Customer Data Platform
    - Identity Resolution
    url: /providers/segment/
  layer: common
  name: Segment
  provider: segment
  says: ships the Segment SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-4220.20
    key: observability-management
    name: Observability Management
    url: /capabilities/observability-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-ready
    agent_readiness: 50.2
    band: exemplar
    in_catalog: true
    kin_score: 80.6
    mcp: &id094
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id095
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.ramp.android.app/latest/
  tier: observed
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
    agent_readiness: 13.6
    band: emerging
    in_catalog: true
    kin_score: 17.9
    mcp: &id002
      status: none
    slug: acumatica
    status: profiled
    tags: &id003
    - Cloud ERP
    - ERP
    - Financial Management
    - Inventory
    url: /providers/acumatica/
  layer: domain
  name: Acumatica
  provider: acumatica
  says: lists Acumatica as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 35.7
    band: developing
    in_catalog: true
    kin_score: 43.7
    mcp: &id004
      status: none
    slug: adp
    status: profiled
    tags: &id005
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
  layer: domain
  name: ADP
  provider: adp
  says: lists ADP as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.6
    mcp: &id006
      status: none
    slug: ally-financial
    status: profiled
    tags: &id007
    - Auto Finance
    - Banking
    - Investing
    - Lending
    url: /providers/ally-financial/
  layer: domain
  name: Ally Bank
  provider: ally-financial
  says: lists Ally Bank as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 13.7
    band: minimal
    in_catalog: true
    kin_score: 8.2
    mcp: &id008
      status: unknown
    slug: alpine-bank
    status: profiled
    tags: &id009
    - Banking
    - Colorado
    - Company
    - Financial Services
    url: /providers/alpine-bank/
  layer: domain
  name: Alpine Bank
  provider: alpine-bank
  says: lists Alpine Bank as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 46.8
    band: developing
    in_catalog: true
    kin_score: 46.7
    mcp: &id010
      source: https://github.com/amzn/selling-partner-agentic-toolkit
      status: verified
    slug: amazon
    status: profiled
    tags: &id011
    - Advertising
    - Alexa
    - Amazon
    - E-Commerce
    url: /providers/amazon/
  layer: domain
  name: Amazon Business
  provider: amazon
  says: lists Amazon Business as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.10
    key: AE-210.10
    name: Flight Search & Booking
    url: /capabilities/flight-search-booking/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.2
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id012
      status: none
    slug: american-airlines
    status: profiled
    tags: &id013
    - Airlines
    - Aviation
    - Flights
    - Travel
    url: /providers/american-airlines/
  layer: domain
  name: American Airlines AAdvantage Business
  provider: american-airlines
  says: lists American Airlines AAdvantage Business as an integration
  source: https://ramp.com/integrations
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
    kin_score: 20.6
    mcp: &id014
      status: none
    slug: aplos
    status: profiled
    tags: &id015
    - Accounting
    - Company
    - Non-Profit
    - Software
    url: /providers/aplos/
  layer: domain
  name: Aplos
  provider: aplos
  says: lists Aplos as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 53.7
    band: exemplar
    in_catalog: true
    kin_score: 74.8
    mcp: &id016
      source: https://developers.asana.com/docs/using-asanas-mcp-server
      status: verified
    slug: asana
    status: profiled
    tags: &id017
    - Collaboration
    - Productivity
    - Project
    - Project Management
    url: /providers/asana/
  layer: common
  name: Asana
  provider: asana
  says: lists Asana as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 26.8
    band: developing
    in_catalog: true
    kin_score: 40.9
    mcp: &id018
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id019
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
  layer: domain
  name: BambooHR
  provider: bamboohr
  says: lists BambooHR as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 29.8
    band: thin
    in_catalog: true
    kin_score: 38.3
    mcp: &id020
      status: none
    slug: bank-of-america
    status: profiled
    tags: &id021
    - Banking
    - Corporate Banking
    - Finance
    - Payments
    url: /providers/bank-of-america/
  layer: domain
  name: Bank of America
  provider: bank-of-america
  says: lists Bank of America as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 32.2
    band: developing
    in_catalog: true
    kin_score: 39.3
    mcp: &id022
      status: none
    slug: blackbaud
    status: profiled
    tags: &id023
    - CRM
    - Donor Management
    - Fundraising
    - Non-Profit
    url: /providers/blackbaud/
  layer: domain
  name: Blackbaud
  provider: blackbaud
  says: lists Blackbaud as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 55.2
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id026
      source: https://docs.campfire.ai/guides/ai-integration
      status: verified
    slug: campfire
    status: profiled
    tags: &id027
    - Accounting
    - Company
    - ERP
    - Finance
    url: /providers/campfire/
  layer: domain
  name: Campfire
  provider: campfire
  says: lists Campfire as an integration
  source: https://ramp.com/integrations
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
    agent_band: agent-aware
    agent_readiness: 27.6
    band: thin
    in_catalog: true
    kin_score: 33.9
    mcp: &id028
      status: none
    slug: cloudeagle
    status: profiled
    tags: &id029
    - Access Governance
    - Cost Optimization
    - License Management
    - Procurement
    url: /providers/cloudeagle/
  layer: domain
  name: CloudEagle
  provider: cloudeagle
  says: lists CloudEagle as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 18.0
    band: emerging
    in_catalog: true
    kin_score: 15.1
    mcp: &id030
      source: https://learning.deltek.com/bundle/MCP_Server_Setup_Guide_for_REST_APIs/page/overview.html
      status: documented
    slug: deltek
    status: profiled
    tags: &id031
    - Company
    - Enterprise
    - Project Management
    - Software
    url: /providers/deltek/
  layer: domain
  name: Deltek Vantagepoint
  provider: deltek
  says: lists Deltek Vantagepoint as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 35.7
    band: strong
    in_catalog: true
    kin_score: 59.9
    mcp: &id032
      source: https://github.com/digits/mcp-skills
      status: documented
    slug: digits-com
    status: profiled
    tags: &id033
    - Accounting
    - Bookkeeping
    - Finance
    - General Ledger
    url: /providers/digits-com/
  layer: domain
  name: Digits
  provider: digits-com
  says: lists Digits as an integration
  source: https://ramp.com/integrations
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
    band: exemplar
    in_catalog: true
    kin_score: 71.4
    mcp: &id034
      source: https://www.docusign.com/products/mcp
      status: documented
    slug: docusign
    status: profiled
    tags: &id035
    - Agreements
    - Contracts
    - DocuSign
    - E-Signature
    url: /providers/docusign/
  layer: common
  name: Docusign
  provider: docusign
  says: lists Docusign as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-140.100.20
    key: AE-140.100.20
    name: Food Delivery
    url: /capabilities/quick-local-commerce/
    via_parent: Quick & Local Commerce
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.5
    band: exemplar
    in_catalog: true
    kin_score: 77.8
    mcp: &id036
      status: none
    slug: doordash
    status: profiled
    tags: &id037
    - Delivery
    - Last Mile Delivery
    - Logistics
    - On-Demand
    url: /providers/doordash/
  layer: domain
  name: DoorDash
  provider: doordash
  says: lists DoorDash as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4290
    key: saas-trust-service-compliance-management
    name: SaaS Trust & Service Compliance Management
    url: /capabilities/saas-trust-service-compliance-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 53.1
    band: exemplar
    in_catalog: true
    kin_score: 70.7
    mcp: &id038
      source: https://developers.drata.com/developer-portal/v2/mcp-server
      status: verified
    slug: drata
    status: profiled
    tags: &id039
    - Compliance
    - GRC
    - ISO 27001
    - SOC 2
    url: /providers/drata/
  layer: common
  name: Drata
  provider: drata
  says: lists Drata as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 45.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id040
      source: https://help.dropbox.com/integrations/connect-dropbox-mcp-server
      status: verified
    slug: dropbox
    status: profiled
    tags: &id041
    - Cloud Storage
    - Collaboration
    - Documents
    - Storage
    url: /providers/dropbox/
  layer: common
  name: Dropbox
  provider: dropbox
  says: lists Dropbox as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 50.0
    band: developing
    in_catalog: true
    kin_score: 49.7
    mcp: &id042
      source: https://docs.dualentry.com/developers/guides/integrations-and-tools/mcp
      status: documented
    slug: dualentry
    status: profiled
    tags: &id043
    - Accounting
    - Artificial Intelligence
    - Company
    - ERP
    url: /providers/dualentry/
  layer: domain
  name: DualEntry
  provider: dualentry
  says: lists DualEntry as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 12.2
    band: emerging
    in_catalog: true
    kin_score: 16.3
    mcp: &id044
      status: none
    slug: finaloop
    status: profiled
    tags: &id045
    - Accounting
    - Bookkeeping
    - Company
    - E-Commerce
    url: /providers/finaloop/
  layer: domain
  name: Finaloop
  provider: finaloop
  says: lists Finaloop as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 48.8
    mcp: &id046
      source: https://github.com/google/mcp
      status: verified
    slug: google-calendar
    status: profiled
    tags: &id047
    - Availability
    - Calendar
    - Event
    - Google
    url: /providers/google-calendar/
  layer: common
  name: Google Calendar
  provider: google-calendar
  says: lists Google Calendar as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 42.0
    mcp: &id048
      status: none
    slug: gusto
    status: profiled
    tags: &id049
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: domain
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 35.3
    band: developing
    in_catalog: true
    kin_score: 53.5
    mcp: &id050
      status: none
    slug: ironclad
    status: profiled
    tags: &id051
    - Contract Lifecycle Management
    - Contracts
    - Legal Tech
    - LegalOps
    url: /providers/ironclad/
  layer: common
  name: Ironclad
  provider: ironclad
  says: lists Ironclad as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 65.7
    band: exemplar
    in_catalog: true
    kin_score: 82.6
    mcp: &id052
      source: https://support.atlassian.com/atlassian-rovo-mcp-server/docs/getting-started-with-the-atlassian-remote-mcp-server/
      status: verified
    slug: jira
    status: profiled
    tags: &id053
    - Agile
    - ITSM
    - Issue Tracking
    - Project Management
    url: /providers/jira/
  layer: common
  name: Jira
  provider: jira
  says: lists Jira as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 41.7
    band: developing
    in_catalog: true
    kin_score: 47.0
    mcp: &id054
      status: none
    slug: justworks
    status: profiled
    tags: &id055
    - Benefits
    - Human Resources
    - PEO
    - Payroll
    url: /providers/justworks/
  layer: domain
  name: Justworks
  provider: justworks
  says: lists Justworks as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 35.5
    band: thin
    in_catalog: true
    kin_score: 38.1
    mcp: &id056
      source: https://linear.app/docs/mcp
      status: verified
    slug: linear-app
    status: profiled
    tags: &id057
    - Issue Tracking
    - Productivity
    - Project Management
    - Software-as-a-Service
    url: /providers/linear-app/
  layer: common
  name: Linear
  provider: linear-app
  says: lists Linear as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 37.1
    band: developing
    in_catalog: true
    kin_score: 50.6
    mcp: &id058
      status: none
    slug: lyft
    status: profiled
    tags: &id059
    - Micromobility
    - Mobility
    - Ride Hailing
    - Transportation
    url: /providers/lyft/
  layer: domain
  name: Lyft
  provider: lyft
  says: lists Lyft as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 33.6
    band: thin
    in_catalog: true
    kin_score: 38.9
    mcp: &id060
      source: https://mercury.com/mcp
      status: verified
    slug: mercury
    status: profiled
    tags: &id061
    - Banking
    - Fintech
    - Startups
    - Treasury
    url: /providers/mercury/
  layer: domain
  name: Mercury
  provider: mercury
  says: lists Mercury as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 36.1
    band: exemplar
    in_catalog: true
    kin_score: 70.2
    mcp: &id062
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id063
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: domain
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 33.1
    band: strong
    in_catalog: true
    kin_score: 63.9
    mcp: &id064
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id065
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics 365 Finance and Operations
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics 365 Finance and Operations as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 34.2
    band: strong
    in_catalog: true
    kin_score: 59.0
    mcp: &id066
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id067
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://ramp.com/integrations
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
    kin_score: 12.5
    mcp: &id068
      status: none
    slug: netsuite
    status: profiled
    tags: &id069
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: NetSuite
  provider: netsuite
  says: lists NetSuite as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 17.9
    band: thin
    in_catalog: true
    kin_score: 27.9
    mcp: &id070
      status: none
    slug: odoo
    status: profiled
    tags: &id071
    - Business Applications
    - CRM
    - ERP
    - Open Source
    url: /providers/odoo/
  layer: domain
  name: Odoo
  provider: odoo
  says: lists Odoo as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 53.8
    band: exemplar
    in_catalog: true
    kin_score: 78.0
    mcp: &id072
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id073
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id074
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id075
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Fusion Cloud
  provider: oracle
  says: lists Oracle Fusion Cloud as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 23.4
    band: thin
    in_catalog: true
    kin_score: 37.9
    mcp: &id076
      status: none
    slug: paychex-developer
    status: profiled
    tags: &id077
    - Benefits
    - HCM
    - Human Resources
    - Paychex Flex
    url: /providers/paychex-developer/
  layer: domain
  name: Paychex
  provider: paychex-developer
  says: lists Paychex as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 23.9
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id078
      status: none
    slug: paylocity
    status: profiled
    tags: &id079
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/paylocity/
  layer: domain
  name: Paylocity
  provider: paylocity
  says: lists Paylocity as an integration
  source: https://ramp.com/integrations
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
    band: developing
    in_catalog: true
    kin_score: 47.6
    mcp: &id080
      source: https://registry.modelcontextprotocol.io/v0/servers?search=io.puzzle/puzzle
      status: verified
    slug: puzzle
    status: profiled
    tags: &id081
    - Accounting
    - Bookkeeping
    - Company
    - Finance
    url: /providers/puzzle/
  layer: domain
  name: Puzzle
  provider: puzzle
  says: lists Puzzle as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 41.2
    band: strong
    in_catalog: true
    kin_score: 61.1
    mcp: &id082
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id083
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Online / Desktop
  provider: quickbooks
  says: lists QuickBooks Online / Desktop as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 50.0
    band: strong
    in_catalog: true
    kin_score: 56.1
    mcp: &id084
      status: none
    slug: rillet
    status: profiled
    tags: &id085
    - Accounting
    - Company
    - ERP
    - Fintech
    url: /providers/rillet/
  layer: domain
  name: Rillet
  provider: rillet
  says: lists Rillet as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 31.3
    band: developing
    in_catalog: true
    kin_score: 41.8
    mcp: &id086
      status: none
    slug: sage
    status: profiled
    tags: &id087
    - Accounting
    - Business Management
    - Cloud Software
    - ERP
    url: /providers/sage/
  layer: domain
  name: Sage 100 / Sage 300
  provider: sage
  says: lists Sage 100 / Sage 300 as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 15.5
    band: thin
    in_catalog: true
    kin_score: 26.3
    mcp: &id088
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id089
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 24.3
    band: emerging
    in_catalog: true
    kin_score: 26.1
    mcp: &id090
      status: none
    slug: sap-successfactors
    status: profiled
    tags: &id091
    - HCM
    - Human Resources
    - Payroll
    - Talent Management
    url: /providers/sap-successfactors/
  layer: domain
  name: SAP SuccessFactors
  provider: sap-successfactors
  says: lists SAP SuccessFactors as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 38.7
    band: exemplar
    in_catalog: true
    kin_score: 74.7
    mcp: &id096
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id097
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://ramp.com/integrations
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
    agent_band: agent-native
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id098
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id099
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square Payroll
  provider: square
  says: lists Square Payroll as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 24.6
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id100
      status: none
    slug: td-bank
    status: profiled
    tags: &id101
    - AML
    - Account Aggregation
    - Akoya
    - Banking
    url: /providers/td-bank/
  layer: domain
  name: TD Bank
  provider: td-bank
  says: lists TD Bank as an integration
  source: https://ramp.com/integrations
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
    agent_band: human-only
    agent_readiness: 3.1
    band: emerging
    in_catalog: true
    kin_score: 16.9
    mcp: &id102
      status: none
    slug: trinet-group
    status: profiled
    tags: &id103
    - Benefits
    - Compliance
    - Human Resources
    - Payroll
    url: /providers/trinet-group/
  layer: domain
  name: TriNet
  provider: trinet-group
  says: lists TriNet as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-210.30.10
    key: AE-210.30.10
    name: Ride Hailing
    url: /capabilities/ground-transport/
    via_parent: Ground Transport
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 21.8
    band: developing
    in_catalog: true
    kin_score: 47.7
    mcp: &id104
      status: none
    slug: uber
    status: profiled
    tags: &id105
    - Food Delivery
    - Ride Hailing
    - Taxis
    - Transportation
    url: /providers/uber/
  layer: domain
  name: Uber
  provider: uber
  says: lists Uber as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 23.7
    band: thin
    in_catalog: true
    kin_score: 31.7
    mcp: &id106
      status: none
    slug: ukg
    status: profiled
    tags: &id107
    - HCM
    - Human Resources
    - Payroll
    - Workforce Management
    url: /providers/ukg/
  layer: domain
  name: UKG Pro / UKG Ready
  provider: ukg
  says: lists UKG Pro / UKG Ready as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 30.2
    band: thin
    in_catalog: true
    kin_score: 28.0
    mcp: &id108
      status: none
    slug: us-bancorp
    status: profiled
    tags: &id109
    - Banking
    - Corporate Banking
    - Finance
    - Fortune 500
    url: /providers/us-bancorp/
  layer: domain
  name: US Bank
  provider: us-bancorp
  says: lists US Bank as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 23.0
    band: developing
    in_catalog: true
    kin_score: 41.1
    mcp: &id110
      status: none
    slug: trimble
    status: profiled
    tags: &id111
    - Construction
    - GPS
    - Geospatial
    - Transportation
    url: /providers/trimble/
  layer: domain
  name: Viewpoint Spectrum / Vista
  provider: trimble
  says: lists Viewpoint Spectrum / Vista as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-210.10
    key: cash-management
    name: Cash Management
    url: /capabilities/cash-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 25.4
    band: developing
    in_catalog: true
    kin_score: 42.9
    mcp: &id112
      status: none
    slug: wells-fargo
    status: profiled
    tags: &id113
    - Banking
    - Consumer Banking
    - Fortune 100
    url: /providers/wells-fargo/
  layer: domain
  name: Wells Fargo
  provider: wells-fargo
  says: lists Wells Fargo as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id114
      status: none
    slug: workday
    status: profiled
    tags: &id115
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://ramp.com/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Workday Financial Management
  provider: workday
  says: lists Workday Financial Management as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 61.3
    band: exemplar
    in_catalog: true
    kin_score: 82.4
    mcp: &id116
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id117
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 25.5
    band: thin
    in_catalog: true
    kin_score: 35.3
    mcp: &id118
      source: https://claude.com/connectors/yardi-virtuoso
      status: documented
    slug: yardi
    status: profiled
    tags: &id119
    - Accounting
    - Co-Working
    - Commercial Real Estate
    - Investment Management
    url: /providers/yardi/
  layer: domain
  name: Yardi
  provider: yardi
  says: lists Yardi as an integration
  source: https://ramp.com/integrations
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
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 20.9
    mcp: &id120
      status: none
    slug: zenefits
    status: profiled
    tags: &id121
    - Benefits Administration
    - HRIS
    - Human Resources
    - Payroll
    url: /providers/zenefits/
  layer: domain
  name: Zenefits
  provider: zenefits
  says: lists Zenefits as an integration
  source: https://ramp.com/integrations
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
    agent_readiness: 18.9
    band: developing
    in_catalog: true
    kin_score: 45.5
    mcp: &id122
      source: https://www.zoho.com/mcp/
      status: documented
    slug: zoho-books
    status: profiled
    tags: &id123
    - Accounting
    - Bookkeeping
    - Expenses
    - Invoicing
    url: /providers/zoho-books/
  layer: domain
  name: Zoho Books
  provider: zoho-books
  says: lists Zoho Books as an integration
  source: https://ramp.com/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/expense-management/ramp/
providers:
- agent_band: agent-aware
  agent_readiness: 13.6
  band: emerging
  in_catalog: true
  kin_score: 17.9
  mcp: *id002
  name: Acumatica
  slug: acumatica
  status: profiled
  tags: *id003
  url: /providers/acumatica/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id004
  name: ADP
  slug: adp
  status: profiled
  tags: *id005
  url: /providers/adp/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.6
  mcp: *id006
  name: Ally Bank
  slug: ally-financial
  status: profiled
  tags: *id007
  url: /providers/ally-financial/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: minimal
  in_catalog: true
  kin_score: 8.2
  mcp: *id008
  name: Alpine Bank
  slug: alpine-bank
  status: profiled
  tags: *id009
  url: /providers/alpine-bank/
- agent_band: agent-ready
  agent_readiness: 46.8
  band: developing
  in_catalog: true
  kin_score: 46.7
  mcp: *id010
  name: Amazon Business
  slug: amazon
  status: profiled
  tags: *id011
  url: /providers/amazon/
- agent_band: agent-aware
  agent_readiness: 17.2
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id012
  name: American Airlines AAdvantage Business
  slug: american-airlines
  status: profiled
  tags: *id013
  url: /providers/american-airlines/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.6
  mcp: *id014
  name: Aplos
  slug: aplos
  status: profiled
  tags: *id015
  url: /providers/aplos/
- agent_band: agent-ready
  agent_readiness: 53.7
  band: exemplar
  in_catalog: true
  kin_score: 74.8
  mcp: *id016
  name: Asana
  slug: asana
  status: profiled
  tags: *id017
  url: /providers/asana/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id018
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id019
  url: /providers/bamboohr/
- agent_band: agent-ready
  agent_readiness: 29.8
  band: thin
  in_catalog: true
  kin_score: 38.3
  mcp: *id020
  name: Bank of America
  slug: bank-of-america
  status: profiled
  tags: *id021
  url: /providers/bank-of-america/
- agent_band: agent-ready
  agent_readiness: 32.2
  band: developing
  in_catalog: true
  kin_score: 39.3
  mcp: *id022
  name: Blackbaud
  slug: blackbaud
  status: profiled
  tags: *id023
  url: /providers/blackbaud/
- agent_band: agent-aware
  agent_readiness: 24.7
  band: emerging
  in_catalog: true
  kin_score: 23.0
  mcp: *id024
  name: Branch
  slug: branch-io
  status: profiled
  tags: *id025
  url: /providers/branch-io/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id026
  name: Campfire
  slug: campfire
  status: profiled
  tags: *id027
  url: /providers/campfire/
- agent_band: agent-aware
  agent_readiness: 27.6
  band: thin
  in_catalog: true
  kin_score: 33.9
  mcp: *id028
  name: CloudEagle
  slug: cloudeagle
  status: profiled
  tags: *id029
  url: /providers/cloudeagle/
- agent_band: agent-aware
  agent_readiness: 18.0
  band: emerging
  in_catalog: true
  kin_score: 15.1
  mcp: *id030
  name: Deltek Vantagepoint
  slug: deltek
  status: profiled
  tags: *id031
  url: /providers/deltek/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id032
  name: Digits
  slug: digits-com
  status: profiled
  tags: *id033
  url: /providers/digits-com/
- agent_band: agent-ready
  agent_readiness: 35.0
  band: exemplar
  in_catalog: true
  kin_score: 71.4
  mcp: *id034
  name: Docusign
  slug: docusign
  status: profiled
  tags: *id035
  url: /providers/docusign/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: exemplar
  in_catalog: true
  kin_score: 77.8
  mcp: *id036
  name: DoorDash
  slug: doordash
  status: profiled
  tags: *id037
  url: /providers/doordash/
- agent_band: agent-ready
  agent_readiness: 53.1
  band: exemplar
  in_catalog: true
  kin_score: 70.7
  mcp: *id038
  name: Drata
  slug: drata
  status: profiled
  tags: *id039
  url: /providers/drata/
- agent_band: agent-ready
  agent_readiness: 45.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id040
  name: Dropbox
  slug: dropbox
  status: profiled
  tags: *id041
  url: /providers/dropbox/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id042
  name: DualEntry
  slug: dualentry
  status: profiled
  tags: *id043
  url: /providers/dualentry/
- agent_band: agent-aware
  agent_readiness: 12.2
  band: emerging
  in_catalog: true
  kin_score: 16.3
  mcp: *id044
  name: Finaloop
  slug: finaloop
  status: profiled
  tags: *id045
  url: /providers/finaloop/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 48.8
  mcp: *id046
  name: Google Calendar
  slug: google-calendar
  status: profiled
  tags: *id047
  url: /providers/google-calendar/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 42.0
  mcp: *id048
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id049
  url: /providers/gusto/
- agent_band: agent-ready
  agent_readiness: 35.3
  band: developing
  in_catalog: true
  kin_score: 53.5
  mcp: *id050
  name: Ironclad
  slug: ironclad
  status: profiled
  tags: *id051
  url: /providers/ironclad/
- agent_band: agent-ready
  agent_readiness: 65.7
  band: exemplar
  in_catalog: true
  kin_score: 82.6
  mcp: *id052
  name: Jira
  slug: jira
  status: profiled
  tags: *id053
  url: /providers/jira/
- agent_band: agent-ready
  agent_readiness: 41.7
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id054
  name: Justworks
  slug: justworks
  status: profiled
  tags: *id055
  url: /providers/justworks/
- agent_band: agent-ready
  agent_readiness: 35.5
  band: thin
  in_catalog: true
  kin_score: 38.1
  mcp: *id056
  name: Linear
  slug: linear-app
  status: profiled
  tags: *id057
  url: /providers/linear-app/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id058
  name: Lyft
  slug: lyft
  status: profiled
  tags: *id059
  url: /providers/lyft/
- agent_band: agent-ready
  agent_readiness: 33.6
  band: thin
  in_catalog: true
  kin_score: 38.9
  mcp: *id060
  name: Mercury
  slug: mercury
  status: profiled
  tags: *id061
  url: /providers/mercury/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id062
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id063
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id064
  name: Microsoft Dynamics 365 Finance and Operations
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id065
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id066
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id067
  url: /providers/microsoft-teams/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id068
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id069
  url: /providers/netsuite/
- agent_band: agent-aware
  agent_readiness: 17.9
  band: thin
  in_catalog: true
  kin_score: 27.9
  mcp: *id070
  name: Odoo
  slug: odoo
  status: profiled
  tags: *id071
  url: /providers/odoo/
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id072
  name: Okta
  slug: okta
  status: profiled
  tags: *id073
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id074
  name: Oracle Fusion Cloud
  slug: oracle
  status: profiled
  tags: *id075
  url: /providers/oracle/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id076
  name: Paychex
  slug: paychex-developer
  status: profiled
  tags: *id077
  url: /providers/paychex-developer/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id078
  name: Paylocity
  slug: paylocity
  status: profiled
  tags: *id079
  url: /providers/paylocity/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id080
  name: Puzzle
  slug: puzzle
  status: profiled
  tags: *id081
  url: /providers/puzzle/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id082
  name: QuickBooks Online / Desktop
  slug: quickbooks
  status: profiled
  tags: *id083
  url: /providers/quickbooks/
- agent_band: agent-native
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id084
  name: Rillet
  slug: rillet
  status: profiled
  tags: *id085
  url: /providers/rillet/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id086
  name: Sage 100 / Sage 300
  slug: sage
  status: profiled
  tags: *id087
  url: /providers/sage/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id088
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id089
  url: /providers/sage-intacct/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id090
  name: SAP SuccessFactors
  slug: sap-successfactors
  status: profiled
  tags: *id091
  url: /providers/sap-successfactors/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 43.8
  mcp: *id092
  name: Segment
  slug: segment
  status: profiled
  tags: *id093
  url: /providers/segment/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id094
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id095
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id096
  name: Slack
  slug: slack
  status: profiled
  tags: *id097
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id098
  name: Square Payroll
  slug: square
  status: profiled
  tags: *id099
  url: /providers/square/
- agent_band: agent-aware
  agent_readiness: 24.6
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id100
  name: TD Bank
  slug: td-bank
  status: profiled
  tags: *id101
  url: /providers/td-bank/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id102
  name: TriNet
  slug: trinet-group
  status: profiled
  tags: *id103
  url: /providers/trinet-group/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id104
  name: Uber
  slug: uber
  status: profiled
  tags: *id105
  url: /providers/uber/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.7
  mcp: *id106
  name: UKG Pro / UKG Ready
  slug: ukg
  status: profiled
  tags: *id107
  url: /providers/ukg/
- agent_band: agent-ready
  agent_readiness: 30.2
  band: thin
  in_catalog: true
  kin_score: 28.0
  mcp: *id108
  name: US Bank
  slug: us-bancorp
  status: profiled
  tags: *id109
  url: /providers/us-bancorp/
- agent_band: agent-aware
  agent_readiness: 23.0
  band: developing
  in_catalog: true
  kin_score: 41.1
  mcp: *id110
  name: Viewpoint Spectrum / Vista
  slug: trimble
  status: profiled
  tags: *id111
  url: /providers/trimble/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: developing
  in_catalog: true
  kin_score: 42.9
  mcp: *id112
  name: Wells Fargo
  slug: wells-fargo
  status: profiled
  tags: *id113
  url: /providers/wells-fargo/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id114
  name: Workday
  slug: workday
  status: profiled
  tags: *id115
  url: /providers/workday/
- agent_band: agent-native
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id116
  name: Xero
  slug: xero
  status: profiled
  tags: *id117
  url: /providers/xero/
- agent_band: agent-aware
  agent_readiness: 25.5
  band: thin
  in_catalog: true
  kin_score: 35.3
  mcp: *id118
  name: Yardi
  slug: yardi
  status: profiled
  tags: *id119
  url: /providers/yardi/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 20.9
  mcp: *id120
  name: Zenefits
  slug: zenefits
  status: profiled
  tags: *id121
  url: /providers/zenefits/
- agent_band: agent-aware
  agent_readiness: 18.9
  band: developing
  in_catalog: true
  kin_score: 45.5
  mcp: *id122
  name: Zoho Books
  slug: zoho-books
  status: profiled
  tags: *id123
  url: /providers/zoho-books/
siblings:
- name: Brex
  rows: 82
  url: /applications/expense-management/brex/
- name: Expensify
  rows: 82
  url: /applications/expense-management/expensify/
- name: IHateMoney
  rows: 1
  url: /applications/expense-management/ihatemoney/
- name: SAP Concur
  rows: 3
  url: /applications/expense-management/sap-concur/
- name: Spliit
  rows: 4
  url: /applications/expense-management/spliit/
- name: Splitwise
  rows: 2
  url: /applications/expense-management/splitwise/
sitemap: true
title: 'Ramp: Expense & Spend Management reference app'
---
