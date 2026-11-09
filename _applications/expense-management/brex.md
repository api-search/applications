---
app: Brex
app_slug: brex
app_url: https://www.brex.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-200.20
  key: accounts-payable-management
  layer: domain
  name: Accounts Payable Management
  providers:
  - Expensify
  - SAP Concur
  url: /capabilities/accounts-payable-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-1340.70
  key: card-transaction-processing-management
  layer: domain
  name: Card Transaction Processing Management
  providers:
  - Conferma
  url: /capabilities/card-transaction-processing-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.10
  key: AE-210.10
  layer: domain
  name: Flight Search & Booking
  providers:
  - Navan
  - Sabre
  url: /capabilities/flight-search-booking/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: domain
  name: General Ledger Management
  providers:
  - Campfire
  - Digits
  - DualEntry
  - Hanover Park
  - Microsoft Dynamics 365 Business Central
  - Microsoft Dynamics 365 F&O
  - Oracle Fusion Cloud ERP
  - Oracle Netsuite
  - Puzzle
  - QuickBooks Desktop / Online
  - Rillet
  - Sage Intacct
  - Workday Financials ERP
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - ADP Workforce Now
  - Alexis
  - Altera Payroll
  - Bamboo HR
  - Breathe
  - Charlie
  - ChartHop
  - ClayHR
  - Dayforce
  - Deel
  - Freshteam
  - Gusto
  - HiBob
  - HR Cloud
  - HR Partner
  - Humaans
  - Insperity Premier
  - IntelliHR
  - Justworks
  - Kallidus
  - Lano
  - Lattice
  - Lucca
  - Namely
  - Nmbrs
  - Officient
  - Oracle Fusion Cloud HCM
  - Paychex
  - Paycor
  - Paylocity
  - Personio
  - ProLiant
  - Rippling
  - Sage HR
  - SAP SuccessFactors
  - Sesame
  - TriNet
  - UKG
  - Workday
  - Zenefits
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-220.20
  key: indirect-tax-management
  layer: domain
  name: Indirect Tax Management
  providers:
  - VAT IT
  url: /capabilities/indirect-tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-2320
  key: point-of-sale-operations-management
  layer: domain
  name: Point of Sale Operations Management
  providers:
  - Square
  url: /capabilities/point-of-sale-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-500
  key: procurement-management
  layer: domain
  name: Procurement Management
  providers:
  - Coupa
  - GEP
  - Zip
  url: /capabilities/procurement-management/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-210.30.10
  key: AE-210.30.10
  layer: domain
  name: Ride Hailing
  providers:
  - Lyft Business
  - Uber for Business
  url: /capabilities/ground-transport/
  via_parent: Ground Transport
- attribution: Turbo EA
  id: BC-220
  key: tax-management
  layer: domain
  name: Tax Management
  providers:
  - Inkle
  url: /capabilities/tax-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-430.50
  key: customer-feedback-management
  layer: common
  name: Customer Feedback Management
  providers:
  - Qualtrics
  url: /capabilities/customer-feedback-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - 1Password
  - Google Workspace
  - Microsoft Azure AD
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
- attribution: Turbo EA
  id: BC-930.60
  key: process-automation-governance
  layer: common
  name: Process Automation Governance
  providers:
  - Dashblock
  url: /capabilities/process-automation-governance/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.60
  key: AE-150.60
  layer: common
  name: Video Calling
  providers:
  - Zoom
  url: /capabilities/video-calling/
  via_parent: null
- attribution: API Evangelist extension
  id: AE-150.20.20
  key: AE-150.20.20
  layer: common
  name: WhatsApp & OTT Messaging
  providers:
  - WhatsApp
  url: /capabilities/sms-messaging-apps/
  via_parent: SMS & Messaging Apps
- attribution: API Evangelist extension
  id: AE-910
  key: AE-910
  layer: common
  name: Workflow Automation & iPaaS
  providers:
  - Pipedream
  - Workato
  - Zapier
  url: /capabilities/process-automation-governance/
  via_parent: Process Automation Governance
- attribution: API Evangelist extension
  id: AE-110.10.10
  key: AE-110.10.10
  layer: agent
  name: Hosted LLM Inference
  providers:
  - ChatGPT
  - Claude
  url: /capabilities/model-inference/
  via_parent: Model Inference
category:
  id: expense-management
  name: Expense & Spend Management
  url: /applications/expense-management/
counts:
  declared: 81
  observed: 1
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.brex.mobile/latest/
- route: integrations page
  url: https://www.brex.com/product/integrations
integrations:
- capability:
    attribution: Turbo EA
    id: BC-430.50
    key: customer-feedback-management
    name: Customer Feedback Management
    url: /capabilities/customer-feedback-management/
    via_parent: null
  credit: Exodus Privacy (reports.exodus-privacy.eu.org)
  facts:
    agent_band: agent-aware
    agent_readiness: 20.0
    band: developing
    in_catalog: true
    kin_score: 47.3
    mcp: &id115
      status: none
    slug: qualtrics
    status: profiled
    tags: &id116
    - Customer Experience
    - Employee Experience
    - Experience Management
    - Surveys
    url: /providers/qualtrics/
  layer: common
  name: Qualtrics
  provider: qualtrics
  says: ships the Qualtrics SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.brex.mobile/latest/
  tier: observed
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
    agent_readiness: 33.8
    band: exemplar
    in_catalog: true
    kin_score: 67.7
    mcp: &id003
      source: https://1password.dev/environments/mcp-server
      status: verified
    slug: 1password
    status: profiled
    tags: &id004
    - Password Manager
    - Passwords
    - Secrets
    - Security
    url: /providers/1password/
  layer: common
  name: 1Password
  provider: 1password
  says: lists 1Password as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id005
      status: none
    slug: adp
    status: profiled
    tags: &id006
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/adp/
  layer: domain
  name: ADP Workforce Now
  provider: adp
  says: lists ADP Workforce Now as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 5.0
    band: emerging
    in_catalog: true
    kin_score: 17.4
    mcp: &id007
      status: unknown
    slug: alexishr
    status: profiled
    tags: &id008
    - AI Chatbot
    - Integration
    - Payroll
    - People Analytics
    url: /providers/alexishr/
  layer: domain
  name: Alexis
  provider: alexishr
  says: lists Alexis as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id009
      status: unchecked
    slug: altera-payroll
    status: queued for profiling
    tags: &id010 []
    url: null
  layer: domain
  name: Altera Payroll
  provider: altera-payroll
  says: lists Altera Payroll as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id011
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id012
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
  layer: domain
  name: Bamboo HR
  provider: bamboohr
  says: lists Bamboo HR as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 20.1
    band: thin
    in_catalog: true
    kin_score: 31.3
    mcp: &id013
      status: none
    slug: breathe-hr
    status: profiled
    tags: &id014
    - Absence Management
    - Employee Management
    - HRIS
    - Human Resources
    url: /providers/breathe-hr/
  layer: domain
  name: Breathe
  provider: breathe-hr
  says: lists Breathe as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id015
      source: https://docs.campfire.ai/guides/ai-integration
      status: verified
    slug: campfire
    status: profiled
    tags: &id016
    - Accounting
    - Company
    - ERP
    - Finance
    url: /providers/campfire/
  layer: domain
  name: Campfire
  provider: campfire
  says: lists Campfire as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 28.8
    band: thin
    in_catalog: true
    kin_score: 31.0
    mcp: &id017
      status: none
    slug: charliehr
    status: profiled
    tags: &id018
    - HRIS
    - Human Resources
    - Leave
    - People
    url: /providers/charliehr/
  layer: domain
  name: Charlie
  provider: charliehr
  says: lists Charlie as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 44.1
    band: strong
    in_catalog: true
    kin_score: 62.2
    mcp: &id019
      status: none
    slug: charthop
    status: profiled
    tags: &id020
    - Company
    - HRIS
    - Human Resources
    - People Analytics
    url: /providers/charthop/
  layer: domain
  name: ChartHop
  provider: charthop
  says: lists ChartHop as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 58.4
    band: exemplar
    in_catalog: true
    kin_score: 81.8
    mcp: &id021
      source: https://platform.openai.com/docs/mcp
      status: verified
    slug: openai
    status: profiled
    tags: &id022
    - Artificial Intelligence
    - Generative AI
    - LLM
    - OpenAI
    url: /providers/openai/
  layer: agent
  name: ChatGPT
  provider: openai
  says: lists ChatGPT as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 47.6
    band: exemplar
    in_catalog: true
    kin_score: 87.5
    mcp: &id023
      source: https://docs.anthropic.com/en/docs/agents-and-tools/mcp-connector
      status: verified
    slug: anthropic
    status: profiled
    tags: &id024
    - Anthropic
    - Artificial Intelligence
    - Claude
    - LLM
    url: /providers/anthropic/
  layer: agent
  name: Claude
  provider: anthropic
  says: lists Claude as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 14.7
    band: thin
    in_catalog: true
    kin_score: 29.1
    mcp: &id025
      source: https://www.clayhr.com/mcp-ai-powered-hr-data-access
      status: verified
    slug: clayhr
    status: profiled
    tags: &id026
    - Artificial Intelligence
    - HRMS
    - Human Resources
    - Software-as-a-Service
    url: /providers/clayhr/
  layer: domain
  name: ClayHR
  provider: clayhr
  says: lists ClayHR as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-1340.70
    key: card-transaction-processing-management
    name: Card Transaction Processing Management
    url: /capabilities/card-transaction-processing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 6.0
    band: minimal
    in_catalog: true
    kin_score: 10.3
    mcp: &id027
      status: unknown
    slug: conferma
    status: profiled
    tags: &id028
    - Company
    - Fintech
    - Payments
    - Virtual Card
    url: /providers/conferma/
  layer: domain
  name: Conferma
  provider: conferma
  says: lists Conferma as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 34.9
    band: developing
    in_catalog: true
    kin_score: 51.9
    mcp: &id029
      status: none
    slug: coupa
    status: profiled
    tags: &id030
    - BSM
    - Business Spend Management
    - Cloud Platform
    - Enterprise
    url: /providers/coupa/
  layer: domain
  name: Coupa
  provider: coupa
  says: lists Coupa as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-930.60
    key: process-automation-governance
    name: Process Automation Governance
    url: /capabilities/process-automation-governance/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id031
      status: unchecked
    slug: dashblock
    status: queued for profiling
    tags: &id032 []
    url: null
  layer: common
  name: Dashblock
  provider: dashblock
  says: lists Dashblock as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 15.1
    band: emerging
    in_catalog: true
    kin_score: 13.6
    mcp: &id033
      status: none
    slug: dayforce
    status: profiled
    tags: &id034
    - Company
    - HCM
    - Payroll
    - Workforce Management
    url: /providers/dayforce/
  layer: domain
  name: Dayforce
  provider: dayforce
  says: lists Dayforce as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 51.7
    band: strong
    in_catalog: true
    kin_score: 63.3
    mcp: &id035
      source: https://developer.deel.com/docs/mcp
      status: documented
    slug: deel-com
    status: profiled
    tags: &id036
    - Employer of Record
    - Global Payroll
    - Human Resources
    - Payroll
    url: /providers/deel-com/
  layer: domain
  name: Deel
  provider: deel-com
  says: lists Deel as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id037
      source: https://github.com/digits/mcp-skills
      status: documented
    slug: digits-com
    status: profiled
    tags: &id038
    - Accounting
    - Bookkeeping
    - Finance
    - General Ledger
    url: /providers/digits-com/
  layer: domain
  name: Digits
  provider: digits-com
  says: lists Digits as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id039
      source: https://docs.dualentry.com/developers/guides/integrations-and-tools/mcp
      status: documented
    slug: dualentry
    status: profiled
    tags: &id040
    - Accounting
    - Artificial Intelligence
    - Company
    - ERP
    url: /providers/dualentry/
  layer: domain
  name: DualEntry
  provider: dualentry
  says: lists DualEntry as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: agent-aware
    agent_readiness: 14.7
    band: thin
    in_catalog: true
    kin_score: 28.5
    mcp: &id041
      status: none
    slug: expensify
    status: profiled
    tags: &id042
    - Corporate Cards
    - Expense Management
    - Expense Reporting
    - Receipt Scanning
    url: /providers/expensify/
  layer: domain
  name: Expensify
  provider: expensify
  says: lists Expensify as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 20.6
    band: emerging
    in_catalog: true
    kin_score: 25.8
    mcp: &id043
      status: none
    slug: freshteam
    status: profiled
    tags: &id044
    - Applicant Tracking
    - HRIS
    - Human Resources
    - Recruiting
    url: /providers/freshteam/
  layer: domain
  name: Freshteam
  provider: freshteam
  says: lists Freshteam as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 22.2
    band: emerging
    in_catalog: true
    kin_score: 19.5
    mcp: &id045
      status: none
    slug: gep
    status: profiled
    tags: &id046
    - Artificial Intelligence
    - Company
    - Procurement
    - Supply Chain
    url: /providers/gep/
  layer: domain
  name: GEP
  provider: gep
  says: lists GEP as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 37.9
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id047
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id048
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id049
      status: none
    slug: gusto
    status: profiled
    tags: &id050
    - Benefits
    - Enterprise Software
    - Human Resources
    - Payroll
    url: /providers/gusto/
  layer: domain
  name: Gusto
  provider: gusto
  says: lists Gusto as an integration
  source: https://www.brex.com/product/integrations
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
    kin_score: 15.3
    mcp: &id051
      status: none
    slug: hanover-park
    status: profiled
    tags: &id052
    - Company
    - Enterprise Software
    - Fund Administration
    - Private Equity
    url: /providers/hanover-park/
  layer: domain
  name: Hanover Park
  provider: hanover-park
  says: lists Hanover Park as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 19.7
    band: thin
    in_catalog: true
    kin_score: 30.4
    mcp: &id053
      source: https://apidocs.hibob.com/docs/hibob-mcp-server
      status: verified
    slug: bob
    status: profiled
    tags: &id054
    - Employee Management
    - HRIS
    - Human Resources
    - Time Off
    url: /providers/bob/
  layer: domain
  name: HiBob
  provider: bob
  says: lists HiBob as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 13.2
    mcp: &id055
      status: none
    slug: hr-cloud
    status: profiled
    tags: &id056
    - Artificial Intelligence
    - Frontline
    - Human Resources
    - Software-as-a-Service
    url: /providers/hr-cloud/
  layer: domain
  name: HR Cloud
  provider: hr-cloud
  says: lists HR Cloud as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 20.7
    band: developing
    in_catalog: true
    kin_score: 45.4
    mcp: &id057
      source: https://github.com/HR-Partner/hrpartner-mcp
      status: verified
    slug: hr-partner
    status: profiled
    tags: &id058
    - Employee Records
    - HRIS
    - Human Resources
    - Leave Management
    url: /providers/hr-partner/
  layer: domain
  name: HR Partner
  provider: hr-partner
  says: lists HR Partner as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 45.2
    band: developing
    in_catalog: true
    kin_score: 53.9
    mcp: &id059
      status: none
    slug: humaans-io
    status: profiled
    tags: &id060
    - HRIS
    - Human Resources
    - People Analytics
    - People Operations
    url: /providers/humaans-io/
  layer: domain
  name: Humaans
  provider: humaans-io
  says: lists Humaans as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220
    key: tax-management
    name: Tax Management
    url: /capabilities/tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.9
    band: emerging
    in_catalog: true
    kin_score: 22.3
    mcp: &id061
      status: unknown
    slug: inkle
    status: profiled
    tags: &id062
    - Accounting
    - Bookkeeping
    - Company
    - Tax
    url: /providers/inkle/
  layer: domain
  name: Inkle
  provider: inkle
  says: lists Inkle as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 10.8
    band: emerging
    in_catalog: true
    kin_score: 14.3
    mcp: &id063
      status: none
    slug: insperity
    status: profiled
    tags: &id064
    - Benefits
    - Fortune 1000
    - Human Resources
    - Payroll
    url: /providers/insperity/
  layer: domain
  name: Insperity Premier
  provider: insperity
  says: lists Insperity Premier as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id065
      status: unchecked
    slug: intelihr
    status: queued for profiling
    tags: &id066 []
    url: null
  layer: domain
  name: IntelliHR
  provider: intelihr
  says: lists IntelliHR as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id067
      status: none
    slug: justworks
    status: profiled
    tags: &id068
    - Benefits
    - Human Resources
    - PEO
    - Payroll
    url: /providers/justworks/
  layer: domain
  name: Justworks
  provider: justworks
  says: lists Justworks as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 9.4
    mcp: &id069
      status: unknown
    slug: kallidus
    status: profiled
    tags: &id070
    - Company
    - Compliance
    - LMS
    - Performance Management
    url: /providers/kallidus/
  layer: domain
  name: Kallidus
  provider: kallidus
  says: lists Kallidus as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 20.2
    mcp: &id071
      status: unknown
    slug: lano
    status: profiled
    tags: &id072
    - Company
    - Employer of Record
    - Global Hiring
    - Payroll
    url: /providers/lano/
  layer: domain
  name: Lano
  provider: lano
  says: lists Lano as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 20.9
    band: thin
    in_catalog: true
    kin_score: 37.0
    mcp: &id073
      status: none
    slug: lattice
    status: profiled
    tags: &id074
    - Human Resources
    - OKRs
    - People Management
    - Performance Management
    url: /providers/lattice/
  layer: domain
  name: Lattice
  provider: lattice
  says: lists Lattice as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 36.8
    band: developing
    in_catalog: true
    kin_score: 41.0
    mcp: &id075
      status: none
    slug: lucca
    status: profiled
    tags: &id076
    - Company
    - Human Resources
    - Payroll
    - Software-as-a-Service
    url: /providers/lucca/
  layer: domain
  name: Lucca
  provider: lucca
  says: lists Lucca as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id077
      status: none
    slug: lyft
    status: profiled
    tags: &id078
    - Micromobility
    - Mobility
    - Ride Hailing
    - Transportation
    url: /providers/lyft/
  layer: domain
  name: Lyft Business
  provider: lyft
  says: lists Lyft Business as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 33.5
    band: exemplar
    in_catalog: true
    kin_score: 73.9
    mcp: &id079
      status: none
    slug: microsoft-entra
    status: profiled
    tags: &id080
    - Authentication
    - Azure AD
    - Entra
    - Identity and Access Management
    url: /providers/microsoft-entra/
  layer: common
  name: Microsoft Azure AD
  provider: microsoft-entra
  says: lists Microsoft Azure AD as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id081
      status: none
    slug: microsoft-dynamics-365-business-central
    status: profiled
    tags: &id082
    - Accounting
    - Cloud ERP
    - ERP
    - Finance
    url: /providers/microsoft-dynamics-365-business-central/
  layer: domain
  name: Microsoft Dynamics 365 Business Central
  provider: microsoft-dynamics-365-business-central
  says: lists Microsoft Dynamics 365 Business Central as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id083
      source: https://github.com/microsoft/Dataverse-MCP
      status: verified
    slug: microsoft-dynamics-365
    status: profiled
    tags: &id084
    - Business Applications
    - CRM
    - Cloud
    - Enterprise
    url: /providers/microsoft-dynamics-365/
  layer: domain
  name: Microsoft Dynamics 365 F&O
  provider: microsoft-dynamics-365
  says: lists Microsoft Dynamics 365 F&O as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id085
      status: none
    slug: microsoft-teams
    status: profiled
    tags: &id086
    - Chat
    - Collaboration
    - Communications
    - Microsoft Teams
    url: /providers/microsoft-teams/
  layer: common
  name: Microsoft Teams
  provider: microsoft-teams
  says: lists Microsoft Teams as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 25.9
    band: strong
    in_catalog: true
    kin_score: 59.6
    mcp: &id087
      status: none
    slug: namely
    status: profiled
    tags: &id088
    - Employee Data
    - HCM
    - Human Resources
    - Payroll
    url: /providers/namely/
  layer: domain
  name: Namely
  provider: namely
  says: lists Namely as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: agent-ready
    agent_readiness: 34.9
    band: thin
    in_catalog: true
    kin_score: 32.7
    mcp: &id089
      source: https://developer.navan.com/mcp/
      status: verified
    slug: navan
    status: profiled
    tags: &id090
    - Corporate Cards
    - Corporate Travel
    - Expense Management
    - Spend Management
    url: /providers/navan/
  layer: domain
  name: Navan
  provider: navan
  says: lists Navan as an integration
  source: https://www.brex.com/product/integrations
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
    kin_score: 30.4
    mcp: &id091
      status: none
    slug: nmbrs
    status: profiled
    tags: &id092
    - Employee Management
    - HRIS
    - Human Resources
    - Payroll
    url: /providers/nmbrs/
  layer: domain
  name: Nmbrs
  provider: nmbrs
  says: lists Nmbrs as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id093
      status: unchecked
    slug: officient
    status: queued for profiling
    tags: &id094 []
    url: null
  layer: domain
  name: Officient
  provider: officient
  says: lists Officient as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id095
      source: https://developer.okta.com/docs/concepts/mcp-server/
      status: verified
    slug: okta
    status: profiled
    tags: &id096
    - Identity
    - Okta
    - SSO
    - Workforce Identity
    url: /providers/okta/
  layer: common
  name: Okta
  provider: okta
  says: lists Okta as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts: &id001
    agent_band: agent-ready
    agent_readiness: 56.3
    band: exemplar
    in_catalog: true
    kin_score: 68.6
    mcp: &id097
      source: https://github.com/oracle/mcp
      status: verified
    slug: oracle
    status: profiled
    tags: &id098
    - Cloud
    - Database
    - Enterprise
    - Oracle
    url: /providers/oracle/
  layer: domain
  name: Oracle Fusion Cloud ERP
  provider: oracle
  says: lists Oracle Fusion Cloud ERP as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts: *id001
  layer: domain
  name: Oracle Fusion Cloud HCM
  provider: oracle
  says: lists Oracle Fusion Cloud HCM as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id099
      status: none
    slug: netsuite
    status: profiled
    tags: &id100
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: domain
  name: Oracle Netsuite
  provider: netsuite
  says: lists Oracle Netsuite as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id101
      status: none
    slug: paychex-developer
    status: profiled
    tags: &id102
    - Benefits
    - HCM
    - Human Resources
    - Paychex Flex
    url: /providers/paychex-developer/
  layer: domain
  name: Paychex
  provider: paychex-developer
  says: lists Paychex as an integration
  source: https://www.brex.com/product/integrations
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
    kin_score: 11.3
    mcp: &id103
      status: none
    slug: paycor
    status: profiled
    tags: &id104
    - Benefits Administration
    - HCM
    - Human Resources
    - Payroll
    url: /providers/paycor/
  layer: domain
  name: Paycor
  provider: paycor
  says: lists Paycor as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id105
      status: none
    slug: paylocity
    status: profiled
    tags: &id106
    - Benefits
    - HCM
    - Human Resources
    - Payroll
    url: /providers/paylocity/
  layer: domain
  name: Paylocity
  provider: paylocity
  says: lists Paylocity as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 41.8
    band: thin
    in_catalog: true
    kin_score: 31.4
    mcp: &id107
      status: none
    slug: personio
    status: profiled
    tags: &id108
    - Applicant Tracking
    - HRIS
    - Human Resources
    - Recruiting
    url: /providers/personio/
  layer: domain
  name: Personio
  provider: personio
  says: lists Personio as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 31.3
    band: exemplar
    in_catalog: true
    kin_score: 67.3
    mcp: &id109
      source: https://pipedream.com/docs/connect/mcp
      status: verified
    slug: pipedream
    status: profiled
    tags: &id110
    - Connect
    - Pipedream
    - Pro-Code-API-Composition
    - Workflows
    url: /providers/pipedream/
  layer: common
  name: Pipedream
  provider: pipedream
  says: lists Pipedream as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 0.0
    band: minimal
    in_catalog: true
    kin_score: 7.0
    mcp: &id111
      status: unknown
    slug: proliant
    status: profiled
    tags: &id112
    - Cloud
    - Human Resources
    - Payroll
    - Software-as-a-Service
    url: /providers/proliant/
  layer: domain
  name: ProLiant
  provider: proliant
  says: lists ProLiant as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id113
      source: https://registry.modelcontextprotocol.io/v0/servers?search=io.puzzle/puzzle
      status: verified
    slug: puzzle
    status: profiled
    tags: &id114
    - Accounting
    - Bookkeeping
    - Company
    - Finance
    url: /providers/puzzle/
  layer: domain
  name: Puzzle
  provider: puzzle
  says: lists Puzzle as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id117
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id118
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: domain
  name: QuickBooks Desktop / Online
  provider: quickbooks
  says: lists QuickBooks Desktop / Online as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id119
      status: none
    slug: rillet
    status: profiled
    tags: &id120
    - Accounting
    - Company
    - ERP
    - Fintech
    url: /providers/rillet/
  layer: domain
  name: Rillet
  provider: rillet
  says: lists Rillet as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 22.4
    band: thin
    in_catalog: true
    kin_score: 32.9
    mcp: &id121
      status: none
    slug: rippling
    status: profiled
    tags: &id122
    - HCM
    - Human Resources
    - IT
    - Payroll
    url: /providers/rippling/
  layer: domain
  name: Rippling
  provider: rippling
  says: lists Rippling as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: agent-ready
    agent_readiness: 45.3
    band: thin
    in_catalog: true
    kin_score: 35.2
    mcp: &id123
      status: none
    slug: sabre
    status: profiled
    tags: &id124
    - Airlines
    - GDS
    - Hotels
    - Travel
    url: /providers/sabre/
  layer: domain
  name: Sabre
  provider: sabre
  says: lists Sabre as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 25.4
    band: thin
    in_catalog: true
    kin_score: 35.6
    mcp: &id125
      status: none
    slug: sage-hr
    status: profiled
    tags: &id126
    - HRIS
    - Human Resources
    - People
    - Small Business
    url: /providers/sage-hr/
  layer: domain
  name: Sage HR
  provider: sage-hr
  says: lists Sage HR as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id127
      status: none
    slug: sage-intacct
    status: profiled
    tags: &id128
    - Accounting
    - ERP
    - Financial Management
    - General Ledger
    url: /providers/sage-intacct/
  layer: domain
  name: Sage Intacct
  provider: sage-intacct
  says: lists Sage Intacct as an integration
  source: https://www.brex.com/product/integrations
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
    agent_band: agent-aware
    agent_readiness: 23.4
    band: developing
    in_catalog: true
    kin_score: 42.2
    mcp: &id129
      status: none
    slug: concur
    status: profiled
    tags: &id130
    - Expense Management
    - Finance
    - Invoices
    - SAP
    url: /providers/concur/
  layer: domain
  name: SAP Concur
  provider: concur
  says: lists SAP Concur as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id131
      status: none
    slug: sap-successfactors
    status: profiled
    tags: &id132
    - HCM
    - Human Resources
    - Payroll
    - Talent Management
    url: /providers/sap-successfactors/
  layer: domain
  name: SAP SuccessFactors
  provider: sap-successfactors
  says: lists SAP SuccessFactors as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 42.4
    band: thin
    in_catalog: true
    kin_score: 27.8
    mcp: &id133
      status: none
    slug: sesame-hr
    status: profiled
    tags: &id134
    - HRIS
    - Human Resources
    - Time Tracking
    - Workforce Management
    url: /providers/sesame-hr/
  layer: domain
  name: Sesame
  provider: sesame-hr
  says: lists Sesame as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id135
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id136
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-2320
    key: point-of-sale-operations-management
    name: Point of Sale Operations Management
    url: /capabilities/point-of-sale-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-native
    agent_readiness: 62.8
    band: exemplar
    in_catalog: true
    kin_score: 76.1
    mcp: &id137
      source: https://developer.squareup.com/docs/mcp
      status: verified
    slug: square
    status: profiled
    tags: &id138
    - Booking
    - Location
    - Restaurant
    - Square
    url: /providers/square/
  layer: domain
  name: Square
  provider: square
  says: lists Square as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id139
      status: none
    slug: trinet-group
    status: profiled
    tags: &id140
    - Benefits
    - Compliance
    - Human Resources
    - Payroll
    url: /providers/trinet-group/
  layer: domain
  name: TriNet
  provider: trinet-group
  says: lists TriNet as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id141
      status: none
    slug: uber
    status: profiled
    tags: &id142
    - Food Delivery
    - Ride Hailing
    - Taxis
    - Transportation
    url: /providers/uber/
  layer: domain
  name: Uber for Business
  provider: uber
  says: lists Uber for Business as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id143
      status: none
    slug: ukg
    status: profiled
    tags: &id144
    - HCM
    - Human Resources
    - Payroll
    - Workforce Management
    url: /providers/ukg/
  layer: domain
  name: UKG
  provider: ukg
  says: lists UKG as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-220.20
    key: indirect-tax-management
    name: Indirect Tax Management
    url: /capabilities/indirect-tax-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 17.3
    band: minimal
    in_catalog: true
    kin_score: 10.0
    mcp: &id145
      status: unknown
    slug: vat-it
    status: profiled
    tags: &id146
    - Artificial Intelligence
    - Company
    - Compliance
    - Tax
    url: /providers/vat-it/
  layer: domain
  name: VAT IT
  provider: vat-it
  says: lists VAT IT as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.20.20
    key: AE-150.20.20
    name: WhatsApp & OTT Messaging
    url: /capabilities/sms-messaging-apps/
    via_parent: SMS & Messaging Apps
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 48.0
    band: exemplar
    in_catalog: true
    kin_score: 68.0
    mcp: &id147
      status: none
    slug: whatsapp
    status: profiled
    tags: &id148
    - Analytics
    - Business Messaging
    - Messaging
    - WhatsApp
    url: /providers/whatsapp/
  layer: common
  name: WhatsApp
  provider: whatsapp
  says: lists WhatsApp as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id149
      source: https://docs.workato.com/mcp.html
      status: verified
    slug: workato
    status: profiled
    tags: &id150
    - AI Agents
    - API Management
    - Automation
    - B2B
    url: /providers/workato/
  layer: common
  name: Workato
  provider: workato
  says: lists Workato as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300
    key: human-capital-management
    name: Human Capital Management
    url: /capabilities/human-capital-management/
    via_parent: null
  credit: null
  facts: &id002
    agent_band: agent-ready
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id151
      status: none
    slug: workday
    status: profiled
    tags: &id152
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-200.10
    key: general-ledger-management
    name: General Ledger Management
    url: /capabilities/general-ledger-management/
    via_parent: null
  credit: null
  facts: *id002
  layer: domain
  name: Workday Financials ERP
  provider: workday
  says: lists Workday Financials ERP as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id153
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id154
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: domain
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 66.2
    band: exemplar
    in_catalog: true
    kin_score: 72.0
    mcp: &id155
      source: https://zapier.com/mcp
      status: verified
    slug: zapier
    status: profiled
    tags: &id156
    - Integration
    - Workflow Automation
    - Zapier
    - iPaaS
    url: /providers/zapier/
  layer: common
  name: Zapier
  provider: zapier
  says: lists Zapier as an integration
  source: https://www.brex.com/product/integrations
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
    mcp: &id157
      status: none
    slug: zenefits
    status: profiled
    tags: &id158
    - Benefits Administration
    - HRIS
    - Human Resources
    - Payroll
    url: /providers/zenefits/
  layer: domain
  name: Zenefits
  provider: zenefits
  says: lists Zenefits as an integration
  source: https://www.brex.com/product/integrations
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
    agent_readiness: 13.6
    band: thin
    in_catalog: true
    kin_score: 26.9
    mcp: &id159
      status: none
    slug: zip
    status: profiled
    tags: &id160
    - Approval Workflows
    - Intake to Pay
    - Procurement
    - Spend Management
    url: /providers/zip/
  layer: domain
  name: Zip
  provider: zip
  says: lists Zip as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
- capability:
    attribution: API Evangelist extension
    id: AE-150.60
    key: AE-150.60
    name: Video Calling
    url: /capabilities/video-calling/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 55.2
    band: strong
    in_catalog: true
    kin_score: 56.2
    mcp: &id161
      source: https://developers.zoom.us/docs/mcp/
      status: verified
    slug: zoom
    status: profiled
    tags: &id162
    - Chat
    - Collaboration
    - Video
    - Zoom
    url: /providers/zoom/
  layer: common
  name: Zoom
  provider: zoom
  says: lists Zoom as an integration
  source: https://www.brex.com/product/integrations
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/expense-management/brex/
providers:
- agent_band: agent-ready
  agent_readiness: 33.8
  band: exemplar
  in_catalog: true
  kin_score: 67.7
  mcp: *id003
  name: 1Password
  slug: 1password
  status: profiled
  tags: *id004
  url: /providers/1password/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: developing
  in_catalog: true
  kin_score: 43.7
  mcp: *id005
  name: ADP Workforce Now
  slug: adp
  status: profiled
  tags: *id006
  url: /providers/adp/
- agent_band: human-only
  agent_readiness: 5.0
  band: emerging
  in_catalog: true
  kin_score: 17.4
  mcp: *id007
  name: Alexis
  slug: alexishr
  status: profiled
  tags: *id008
  url: /providers/alexishr/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id009
  name: Altera Payroll
  slug: altera-payroll
  status: queued for profiling
  tags: *id010
  url: null
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id011
  name: Bamboo HR
  slug: bamboohr
  status: profiled
  tags: *id012
  url: /providers/bamboohr/
- agent_band: agent-aware
  agent_readiness: 20.1
  band: thin
  in_catalog: true
  kin_score: 31.3
  mcp: *id013
  name: Breathe
  slug: breathe-hr
  status: profiled
  tags: *id014
  url: /providers/breathe-hr/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id015
  name: Campfire
  slug: campfire
  status: profiled
  tags: *id016
  url: /providers/campfire/
- agent_band: agent-ready
  agent_readiness: 28.8
  band: thin
  in_catalog: true
  kin_score: 31.0
  mcp: *id017
  name: Charlie
  slug: charliehr
  status: profiled
  tags: *id018
  url: /providers/charliehr/
- agent_band: agent-ready
  agent_readiness: 44.1
  band: strong
  in_catalog: true
  kin_score: 62.2
  mcp: *id019
  name: ChartHop
  slug: charthop
  status: profiled
  tags: *id020
  url: /providers/charthop/
- agent_band: agent-native
  agent_readiness: 58.4
  band: exemplar
  in_catalog: true
  kin_score: 81.8
  mcp: *id021
  name: ChatGPT
  slug: openai
  status: profiled
  tags: *id022
  url: /providers/openai/
- agent_band: agent-ready
  agent_readiness: 47.6
  band: exemplar
  in_catalog: true
  kin_score: 87.5
  mcp: *id023
  name: Claude
  slug: anthropic
  status: profiled
  tags: *id024
  url: /providers/anthropic/
- agent_band: agent-aware
  agent_readiness: 14.7
  band: thin
  in_catalog: true
  kin_score: 29.1
  mcp: *id025
  name: ClayHR
  slug: clayhr
  status: profiled
  tags: *id026
  url: /providers/clayhr/
- agent_band: agent-aware
  agent_readiness: 6.0
  band: minimal
  in_catalog: true
  kin_score: 10.3
  mcp: *id027
  name: Conferma
  slug: conferma
  status: profiled
  tags: *id028
  url: /providers/conferma/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: developing
  in_catalog: true
  kin_score: 51.9
  mcp: *id029
  name: Coupa
  slug: coupa
  status: profiled
  tags: *id030
  url: /providers/coupa/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id031
  name: Dashblock
  slug: dashblock
  status: queued for profiling
  tags: *id032
  url: null
- agent_band: agent-aware
  agent_readiness: 15.1
  band: emerging
  in_catalog: true
  kin_score: 13.6
  mcp: *id033
  name: Dayforce
  slug: dayforce
  status: profiled
  tags: *id034
  url: /providers/dayforce/
- agent_band: agent-native
  agent_readiness: 51.7
  band: strong
  in_catalog: true
  kin_score: 63.3
  mcp: *id035
  name: Deel
  slug: deel-com
  status: profiled
  tags: *id036
  url: /providers/deel-com/
- agent_band: agent-ready
  agent_readiness: 35.7
  band: strong
  in_catalog: true
  kin_score: 59.9
  mcp: *id037
  name: Digits
  slug: digits-com
  status: profiled
  tags: *id038
  url: /providers/digits-com/
- agent_band: agent-ready
  agent_readiness: 50.0
  band: developing
  in_catalog: true
  kin_score: 49.7
  mcp: *id039
  name: DualEntry
  slug: dualentry
  status: profiled
  tags: *id040
  url: /providers/dualentry/
- agent_band: agent-aware
  agent_readiness: 14.7
  band: thin
  in_catalog: true
  kin_score: 28.5
  mcp: *id041
  name: Expensify
  slug: expensify
  status: profiled
  tags: *id042
  url: /providers/expensify/
- agent_band: agent-aware
  agent_readiness: 20.6
  band: emerging
  in_catalog: true
  kin_score: 25.8
  mcp: *id043
  name: Freshteam
  slug: freshteam
  status: profiled
  tags: *id044
  url: /providers/freshteam/
- agent_band: agent-aware
  agent_readiness: 22.2
  band: emerging
  in_catalog: true
  kin_score: 19.5
  mcp: *id045
  name: GEP
  slug: gep
  status: profiled
  tags: *id046
  url: /providers/gep/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id047
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id048
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 42.0
  mcp: *id049
  name: Gusto
  slug: gusto
  status: profiled
  tags: *id050
  url: /providers/gusto/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.3
  mcp: *id051
  name: Hanover Park
  slug: hanover-park
  status: profiled
  tags: *id052
  url: /providers/hanover-park/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id053
  name: HiBob
  slug: bob
  status: profiled
  tags: *id054
  url: /providers/bob/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 13.2
  mcp: *id055
  name: HR Cloud
  slug: hr-cloud
  status: profiled
  tags: *id056
  url: /providers/hr-cloud/
- agent_band: agent-aware
  agent_readiness: 20.7
  band: developing
  in_catalog: true
  kin_score: 45.4
  mcp: *id057
  name: HR Partner
  slug: hr-partner
  status: profiled
  tags: *id058
  url: /providers/hr-partner/
- agent_band: agent-ready
  agent_readiness: 45.2
  band: developing
  in_catalog: true
  kin_score: 53.9
  mcp: *id059
  name: Humaans
  slug: humaans-io
  status: profiled
  tags: *id060
  url: /providers/humaans-io/
- agent_band: human-only
  agent_readiness: 2.9
  band: emerging
  in_catalog: true
  kin_score: 22.3
  mcp: *id061
  name: Inkle
  slug: inkle
  status: profiled
  tags: *id062
  url: /providers/inkle/
- agent_band: agent-aware
  agent_readiness: 10.8
  band: emerging
  in_catalog: true
  kin_score: 14.3
  mcp: *id063
  name: Insperity Premier
  slug: insperity
  status: profiled
  tags: *id064
  url: /providers/insperity/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id065
  name: IntelliHR
  slug: intelihr
  status: queued for profiling
  tags: *id066
  url: null
- agent_band: agent-ready
  agent_readiness: 41.7
  band: developing
  in_catalog: true
  kin_score: 47.0
  mcp: *id067
  name: Justworks
  slug: justworks
  status: profiled
  tags: *id068
  url: /providers/justworks/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 9.4
  mcp: *id069
  name: Kallidus
  slug: kallidus
  status: profiled
  tags: *id070
  url: /providers/kallidus/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 20.2
  mcp: *id071
  name: Lano
  slug: lano
  status: profiled
  tags: *id072
  url: /providers/lano/
- agent_band: agent-aware
  agent_readiness: 20.9
  band: thin
  in_catalog: true
  kin_score: 37.0
  mcp: *id073
  name: Lattice
  slug: lattice
  status: profiled
  tags: *id074
  url: /providers/lattice/
- agent_band: agent-ready
  agent_readiness: 36.8
  band: developing
  in_catalog: true
  kin_score: 41.0
  mcp: *id075
  name: Lucca
  slug: lucca
  status: profiled
  tags: *id076
  url: /providers/lucca/
- agent_band: agent-ready
  agent_readiness: 37.1
  band: developing
  in_catalog: true
  kin_score: 50.6
  mcp: *id077
  name: Lyft Business
  slug: lyft
  status: profiled
  tags: *id078
  url: /providers/lyft/
- agent_band: agent-ready
  agent_readiness: 33.5
  band: exemplar
  in_catalog: true
  kin_score: 73.9
  mcp: *id079
  name: Microsoft Azure AD
  slug: microsoft-entra
  status: profiled
  tags: *id080
  url: /providers/microsoft-entra/
- agent_band: agent-ready
  agent_readiness: 36.1
  band: exemplar
  in_catalog: true
  kin_score: 70.2
  mcp: *id081
  name: Microsoft Dynamics 365 Business Central
  slug: microsoft-dynamics-365-business-central
  status: profiled
  tags: *id082
  url: /providers/microsoft-dynamics-365-business-central/
- agent_band: agent-ready
  agent_readiness: 33.1
  band: strong
  in_catalog: true
  kin_score: 63.9
  mcp: *id083
  name: Microsoft Dynamics 365 F&O
  slug: microsoft-dynamics-365
  status: profiled
  tags: *id084
  url: /providers/microsoft-dynamics-365/
- agent_band: agent-ready
  agent_readiness: 34.2
  band: strong
  in_catalog: true
  kin_score: 59.0
  mcp: *id085
  name: Microsoft Teams
  slug: microsoft-teams
  status: profiled
  tags: *id086
  url: /providers/microsoft-teams/
- agent_band: agent-aware
  agent_readiness: 25.9
  band: strong
  in_catalog: true
  kin_score: 59.6
  mcp: *id087
  name: Namely
  slug: namely
  status: profiled
  tags: *id088
  url: /providers/namely/
- agent_band: agent-ready
  agent_readiness: 34.9
  band: thin
  in_catalog: true
  kin_score: 32.7
  mcp: *id089
  name: Navan
  slug: navan
  status: profiled
  tags: *id090
  url: /providers/navan/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id091
  name: Nmbrs
  slug: nmbrs
  status: profiled
  tags: *id092
  url: /providers/nmbrs/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id093
  name: Officient
  slug: officient
  status: queued for profiling
  tags: *id094
  url: null
- agent_band: agent-ready
  agent_readiness: 53.8
  band: exemplar
  in_catalog: true
  kin_score: 78.0
  mcp: *id095
  name: Okta
  slug: okta
  status: profiled
  tags: *id096
  url: /providers/okta/
- agent_band: agent-ready
  agent_readiness: 56.3
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id097
  name: Oracle Fusion Cloud ERP
  slug: oracle
  status: profiled
  tags: *id098
  url: /providers/oracle/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id099
  name: Oracle Netsuite
  slug: netsuite
  status: profiled
  tags: *id100
  url: /providers/netsuite/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: thin
  in_catalog: true
  kin_score: 37.9
  mcp: *id101
  name: Paychex
  slug: paychex-developer
  status: profiled
  tags: *id102
  url: /providers/paychex-developer/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 11.3
  mcp: *id103
  name: Paycor
  slug: paycor
  status: profiled
  tags: *id104
  url: /providers/paycor/
- agent_band: agent-aware
  agent_readiness: 23.9
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id105
  name: Paylocity
  slug: paylocity
  status: profiled
  tags: *id106
  url: /providers/paylocity/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id107
  name: Personio
  slug: personio
  status: profiled
  tags: *id108
  url: /providers/personio/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: exemplar
  in_catalog: true
  kin_score: 67.3
  mcp: *id109
  name: Pipedream
  slug: pipedream
  status: profiled
  tags: *id110
  url: /providers/pipedream/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.0
  mcp: *id111
  name: ProLiant
  slug: proliant
  status: profiled
  tags: *id112
  url: /providers/proliant/
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id113
  name: Puzzle
  slug: puzzle
  status: profiled
  tags: *id114
  url: /providers/puzzle/
- agent_band: agent-aware
  agent_readiness: 20.0
  band: developing
  in_catalog: true
  kin_score: 47.3
  mcp: *id115
  name: Qualtrics
  slug: qualtrics
  status: profiled
  tags: *id116
  url: /providers/qualtrics/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id117
  name: QuickBooks Desktop / Online
  slug: quickbooks
  status: profiled
  tags: *id118
  url: /providers/quickbooks/
- agent_band: agent-native
  agent_readiness: 50.0
  band: strong
  in_catalog: true
  kin_score: 56.1
  mcp: *id119
  name: Rillet
  slug: rillet
  status: profiled
  tags: *id120
  url: /providers/rillet/
- agent_band: agent-aware
  agent_readiness: 22.4
  band: thin
  in_catalog: true
  kin_score: 32.9
  mcp: *id121
  name: Rippling
  slug: rippling
  status: profiled
  tags: *id122
  url: /providers/rippling/
- agent_band: agent-ready
  agent_readiness: 45.3
  band: thin
  in_catalog: true
  kin_score: 35.2
  mcp: *id123
  name: Sabre
  slug: sabre
  status: profiled
  tags: *id124
  url: /providers/sabre/
- agent_band: agent-aware
  agent_readiness: 25.4
  band: thin
  in_catalog: true
  kin_score: 35.6
  mcp: *id125
  name: Sage HR
  slug: sage-hr
  status: profiled
  tags: *id126
  url: /providers/sage-hr/
- agent_band: agent-aware
  agent_readiness: 15.5
  band: thin
  in_catalog: true
  kin_score: 26.3
  mcp: *id127
  name: Sage Intacct
  slug: sage-intacct
  status: profiled
  tags: *id128
  url: /providers/sage-intacct/
- agent_band: agent-aware
  agent_readiness: 23.4
  band: developing
  in_catalog: true
  kin_score: 42.2
  mcp: *id129
  name: SAP Concur
  slug: concur
  status: profiled
  tags: *id130
  url: /providers/concur/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id131
  name: SAP SuccessFactors
  slug: sap-successfactors
  status: profiled
  tags: *id132
  url: /providers/sap-successfactors/
- agent_band: agent-ready
  agent_readiness: 42.4
  band: thin
  in_catalog: true
  kin_score: 27.8
  mcp: *id133
  name: Sesame
  slug: sesame-hr
  status: profiled
  tags: *id134
  url: /providers/sesame-hr/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id135
  name: Slack
  slug: slack
  status: profiled
  tags: *id136
  url: /providers/slack/
- agent_band: agent-native
  agent_readiness: 62.8
  band: exemplar
  in_catalog: true
  kin_score: 76.1
  mcp: *id137
  name: Square
  slug: square
  status: profiled
  tags: *id138
  url: /providers/square/
- agent_band: human-only
  agent_readiness: 3.1
  band: emerging
  in_catalog: true
  kin_score: 16.9
  mcp: *id139
  name: TriNet
  slug: trinet-group
  status: profiled
  tags: *id140
  url: /providers/trinet-group/
- agent_band: agent-aware
  agent_readiness: 21.8
  band: developing
  in_catalog: true
  kin_score: 47.7
  mcp: *id141
  name: Uber for Business
  slug: uber
  status: profiled
  tags: *id142
  url: /providers/uber/
- agent_band: agent-aware
  agent_readiness: 23.7
  band: thin
  in_catalog: true
  kin_score: 31.7
  mcp: *id143
  name: UKG
  slug: ukg
  status: profiled
  tags: *id144
  url: /providers/ukg/
- agent_band: agent-aware
  agent_readiness: 17.3
  band: minimal
  in_catalog: true
  kin_score: 10.0
  mcp: *id145
  name: VAT IT
  slug: vat-it
  status: profiled
  tags: *id146
  url: /providers/vat-it/
- agent_band: agent-ready
  agent_readiness: 48.0
  band: exemplar
  in_catalog: true
  kin_score: 68.0
  mcp: *id147
  name: WhatsApp
  slug: whatsapp
  status: profiled
  tags: *id148
  url: /providers/whatsapp/
- agent_band: agent-ready
  agent_readiness: 54.9
  band: exemplar
  in_catalog: true
  kin_score: 69.2
  mcp: *id149
  name: Workato
  slug: workato
  status: profiled
  tags: *id150
  url: /providers/workato/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id151
  name: Workday
  slug: workday
  status: profiled
  tags: *id152
  url: /providers/workday/
- agent_band: agent-native
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id153
  name: Xero
  slug: xero
  status: profiled
  tags: *id154
  url: /providers/xero/
- agent_band: agent-ready
  agent_readiness: 66.2
  band: exemplar
  in_catalog: true
  kin_score: 72.0
  mcp: *id155
  name: Zapier
  slug: zapier
  status: profiled
  tags: *id156
  url: /providers/zapier/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 20.9
  mcp: *id157
  name: Zenefits
  slug: zenefits
  status: profiled
  tags: *id158
  url: /providers/zenefits/
- agent_band: agent-aware
  agent_readiness: 13.6
  band: thin
  in_catalog: true
  kin_score: 26.9
  mcp: *id159
  name: Zip
  slug: zip
  status: profiled
  tags: *id160
  url: /providers/zip/
- agent_band: agent-ready
  agent_readiness: 55.2
  band: strong
  in_catalog: true
  kin_score: 56.2
  mcp: *id161
  name: Zoom
  slug: zoom
  status: profiled
  tags: *id162
  url: /providers/zoom/
siblings:
- name: Expensify
  rows: 82
  url: /applications/expense-management/expensify/
- name: IHateMoney
  rows: 1
  url: /applications/expense-management/ihatemoney/
- name: Ramp
  rows: 62
  url: /applications/expense-management/ramp/
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
title: 'Brex: Expense & Spend Management reference app'
---
