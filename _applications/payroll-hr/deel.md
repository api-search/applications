---
app: Deel
app_slug: deel
app_url: https://www.deel.com/
author: API Evangelist
capabilities:
- attribution: Turbo EA
  id: BC-300.30
  key: compensation-benefits-management
  layer: domain
  name: Compensation & Benefits Management
  providers:
  - Employee Navigator
  - Human Interest
  - Pave
  url: /capabilities/compensation-benefits-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.60
  key: employee-experience-management
  layer: domain
  name: Employee Experience Management
  providers:
  - Snappy Gifts
  url: /capabilities/employee-experience-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.70
  key: hr-operations-management
  layer: domain
  name: HR Operations Management
  providers:
  - Hofy
  url: /capabilities/hr-operations-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300
  key: human-capital-management
  layer: domain
  name: Human Capital Management
  providers:
  - BambooHR
  - HiBob
  - Personio
  - SAP SuccessFactors
  - Workday
  url: /capabilities/human-capital-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4320
  key: professional-workforce-resourcing-management
  layer: domain
  name: Professional Workforce Resourcing Management
  providers:
  - Pangea (contract-to-hire)
  - Pro5
  - Webstarted
  url: /capabilities/professional-workforce-resourcing-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-300.10
  key: talent-acquisition-management
  layer: domain
  name: Talent Acquisition Management
  providers:
  - Ashby
  - FloCareer
  - Greenhouse
  - JobzMall
  url: /capabilities/talent-acquisition-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-4330.10
  key: timekeeping-management
  layer: domain
  name: Timekeeping Management
  providers:
  - Hubstaff
  - Time Doctor
  url: /capabilities/timekeeping-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.20
  key: accounts-payable-management
  layer: common
  name: Accounts Payable Management
  providers:
  - Moss (getmoss.com)
  - Spendesk
  url: /capabilities/accounts-payable-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-200.10
  key: general-ledger-management
  layer: common
  name: General Ledger Management
  providers:
  - DATEV
  - Fizard
  - NetSuite
  - Puzzle Financial
  - QuickBooks
  - Sage
  - Xero
  url: /capabilities/general-ledger-management/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.20
  key: identity-access-management
  layer: common
  name: Identity & Access Management
  providers:
  - Google Workspace
  - JumpCloud
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
  - Amplitude
  - Firebase (Crashlytics / Analytics)
  url: /capabilities/product-usage-analytics/
  via_parent: null
- attribution: Turbo EA
  id: BC-620.30
  key: threat-detection-response-management
  layer: common
  name: Threat Detection & Response Management
  providers:
  - CrowdStrike
  url: /capabilities/threat-detection-response-management/
  via_parent: null
category:
  id: payroll-hr
  name: HR, Payroll & People Ops
  url: /applications/payroll-hr/
counts:
  declared: 32
  observed: 3
credits:
- Exodus Privacy (reports.exodus-privacy.eu.org)
evidence:
- route: Android build analysis (Exodus Privacy, reports.exodus-privacy.eu.org)
  url: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
- route: integrations page
  url: https://www.deel.com/integrations/
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
    agent_readiness: 56.7
    band: strong
    in_catalog: true
    kin_score: 63.5
    mcp: &id001
      source: https://amplitude.com/docs/amplitude-ai/amplitude-mcp
      status: verified
    slug: amplitude
    status: profiled
    tags: &id002
    - A/B Testing
    - Analytics
    - Experimentation
    - Feature Flags
    url: /providers/amplitude/
  layer: common
  name: Amplitude
  provider: amplitude
  says: ships the Amplitude SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
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
    agent_readiness: 14.2
    band: developing
    in_catalog: true
    kin_score: 50.3
    mcp: &id013
      source: https://firebase.google.com/docs/ai-assistance/mcp-server
      status: verified
    slug: firebase
    status: profiled
    tags: &id014
    - Application Development
    - Backend-as-a-Service
    - Company
    - Mobile
    url: /providers/firebase/
  layer: common
  name: Firebase (Crashlytics / Analytics)
  provider: firebase
  says: ships the Firebase (Crashlytics / Analytics) SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
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
    mcp: &id055
      source: https://docs.sentry.io/product/sentry-mcp/
      status: verified
    slug: sentry-system
    status: profiled
    tags: &id056
    - APM
    - Application Monitoring
    - Bug Tracking
    - Developer Tools
    url: /providers/sentry-system/
  layer: common
  name: Sentry
  provider: sentry-system
  says: ships the Sentry SDK or integration code
  source: https://reports.exodus-privacy.eu.org/en/reports/com.deel.app/latest/
  tier: observed
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 31.9
    band: developing
    in_catalog: true
    kin_score: 52.4
    mcp: &id003
      status: none
    slug: ashby
    status: profiled
    tags: &id004
    - Analytics
    - Applicant Tracking
    - Human Resources
    - Recruiting
    url: /providers/ashby/
  layer: domain
  name: Ashby
  provider: ashby
  says: lists Ashby as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id005
      source: https://documentation.bamboohr.com/docs/mcp-server
      status: verified
    slug: bamboohr
    status: profiled
    tags: &id006
    - HRIS
    - Human Resources
    - Payroll
    - Time Tracking
    url: /providers/bamboohr/
  layer: domain
  name: BambooHR
  provider: bamboohr
  says: lists BambooHR as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-620.30
    key: threat-detection-response-management
    name: Threat Detection & Response Management
    url: /capabilities/threat-detection-response-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 35.1
    band: exemplar
    in_catalog: true
    kin_score: 67.2
    mcp: &id007
      source: https://github.com/CrowdStrike/falcon-mcp
      status: verified
    slug: crowdstrike
    status: profiled
    tags: &id008
    - Cybersecurity
    - Endpoint Detection and Response
    - Endpoint Security
    - Threat Intelligence
    url: /providers/crowdstrike/
  layer: common
  name: CrowdStrike
  provider: crowdstrike
  says: lists CrowdStrike as an integration
  source: https://www.deel.com/integrations/
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
    band: minimal
    in_catalog: true
    kin_score: 7.2
    mcp: &id009
      status: none
    slug: datev
    status: profiled
    tags: &id010
    - Accounting
    - Company
    - Software
    - Tax
    url: /providers/datev/
  layer: common
  name: DATEV
  provider: datev
  says: lists DATEV as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.30
    key: compensation-benefits-management
    name: Compensation & Benefits Management
    url: /capabilities/compensation-benefits-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: emerging
    in_catalog: true
    kin_score: 25.1
    mcp: &id011
      status: none
    slug: employeenavigator
    status: profiled
    tags: &id012
    - Benefits Administration
    - Company
    - Human Resources
    - Insurance
    url: /providers/employeenavigator/
  layer: domain
  name: Employee Navigator
  provider: employeenavigator
  says: lists Employee Navigator as an integration
  source: https://www.deel.com/integrations/
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
    agent_readiness: 8.6
    band: minimal
    in_catalog: true
    kin_score: 9.5
    mcp: &id015
      status: unknown
    slug: fizard
    status: profiled
    tags: &id016
    - Accounting
    - Automation
    - Integration
    - Payments
    url: /providers/fizard/
  layer: common
  name: Fizard
  provider: fizard
  says: lists Fizard as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.5
    mcp: &id017
      status: unknown
    slug: flocareer
    status: profiled
    tags: &id018
    - Artificial Intelligence
    - Company
    - Hiring
    - Interview
    url: /providers/flocareer/
  layer: domain
  name: FloCareer
  provider: flocareer
  says: lists FloCareer as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id019
      source: https://github.com/gemini-cli-extensions/workspace
      status: verified
    slug: google-workspace
    status: profiled
    tags: &id020
    - Calendar
    - Collaboration
    - Email
    - Productivity
    url: /providers/google-workspace/
  layer: common
  name: Google Workspace
  provider: google-workspace
  says: lists Google Workspace as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 58.8
    band: exemplar
    in_catalog: true
    kin_score: 79.7
    mcp: &id021
      status: none
    slug: greenhouse
    status: profiled
    tags: &id022
    - Applicant Tracking
    - Greenhouse
    - Human Resources
    - Recruiting
    url: /providers/greenhouse/
  layer: domain
  name: Greenhouse
  provider: greenhouse
  says: lists Greenhouse as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id023
      source: https://apidocs.hibob.com/docs/hibob-mcp-server
      status: verified
    slug: bob
    status: profiled
    tags: &id024
    - Employee Management
    - HRIS
    - Human Resources
    - Time Off
    url: /providers/bob/
  layer: domain
  name: HiBob
  provider: bob
  says: lists HiBob as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.70
    key: hr-operations-management
    name: HR Operations Management
    url: /capabilities/hr-operations-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id025
      status: unchecked
    slug: hofy
    status: queued for profiling
    tags: &id026 []
    url: null
  layer: domain
  name: Hofy
  provider: hofy
  says: lists Hofy as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 39.7
    band: thin
    in_catalog: true
    kin_score: 33.7
    mcp: &id027
      status: none
    slug: hubstaff
    status: profiled
    tags: &id028
    - Productivity
    - Time Tracking
    - Timesheets
    - Workforce Management
    url: /providers/hubstaff/
  layer: domain
  name: Hubstaff
  provider: hubstaff
  says: lists Hubstaff as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.30
    key: compensation-benefits-management
    name: Compensation & Benefits Management
    url: /capabilities/compensation-benefits-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-aware
    agent_readiness: 19.8
    band: developing
    in_catalog: true
    kin_score: 47.9
    mcp: &id029
      status: none
    slug: human-interest
    status: profiled
    tags: &id030
    - 401k
    - Company
    - Fintech
    - Retirement
    url: /providers/human-interest/
  layer: domain
  name: Human Interest
  provider: human-interest
  says: lists Human Interest as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.10
    key: talent-acquisition-management
    name: Talent Acquisition Management
    url: /capabilities/talent-acquisition-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 22.1
    mcp: &id031
      status: none
    slug: jobzmall
    status: profiled
    tags: &id032
    - Company
    - Marketplace
    - Talent
    - Video
    url: /providers/jobzmall/
  layer: domain
  name: JobzMall
  provider: jobzmall
  says: lists JobzMall as an integration
  source: https://www.deel.com/integrations/
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
    agent_band: agent-aware
    agent_readiness: 23.2
    band: thin
    in_catalog: true
    kin_score: 34.0
    mcp: &id033
      source: https://registry.modelcontextprotocol.io/v0/servers?search=jumpcloud
      status: verified
    slug: jumpcloud
    status: profiled
    tags: &id034
    - Directory Services
    - Identity
    - MFA
    - SSO
    url: /providers/jumpcloud/
  layer: common
  name: JumpCloud
  provider: jumpcloud
  says: lists JumpCloud as an integration
  source: https://www.deel.com/integrations/
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
    agent_readiness: 13.7
    band: emerging
    in_catalog: true
    kin_score: 17.3
    mcp: &id035
      source: https://www.getmoss.com
      status: documented
    slug: getmoss
    status: profiled
    tags: &id036
    - Artificial Intelligence
    - Automation
    - Company
    - Finance
    url: /providers/getmoss/
  layer: common
  name: Moss (getmoss.com)
  provider: getmoss
  says: lists Moss (getmoss.com) as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id037
      status: none
    slug: netsuite
    status: profiled
    tags: &id038
    - Accounting
    - CRM
    - ERP
    - Finance
    url: /providers/netsuite/
  layer: common
  name: NetSuite
  provider: netsuite
  says: lists NetSuite as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4320
    key: professional-workforce-resourcing-management
    name: Professional Workforce Resourcing Management
    url: /capabilities/professional-workforce-resourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 14.1
    mcp: &id039
      status: unknown
    slug: pangea-io
    status: profiled
    tags: &id040
    - Company
    - FX Hedging
    - Finance
    - Risk Management
    url: /providers/pangea-io/
  layer: domain
  name: Pangea (contract-to-hire)
  provider: pangea-io
  says: lists Pangea (contract-to-hire) as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.30
    key: compensation-benefits-management
    name: Compensation & Benefits Management
    url: /capabilities/compensation-benefits-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 17.5
    mcp: &id041
      status: none
    slug: pave
    status: profiled
    tags: &id042
    - Company
    - Compensation
    - Compensation Benchmarking
    - Human Resources
    url: /providers/pave/
  layer: domain
  name: Pave
  provider: pave
  says: lists Pave as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id043
      status: none
    slug: personio
    status: profiled
    tags: &id044
    - Applicant Tracking
    - HRIS
    - Human Resources
    - Recruiting
    url: /providers/personio/
  layer: domain
  name: Personio
  provider: personio
  says: lists Personio as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4320
    key: professional-workforce-resourcing-management
    name: Professional Workforce Resourcing Management
    url: /capabilities/professional-workforce-resourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: null
    agent_readiness: null
    band: null
    in_catalog: false
    kin_score: null
    mcp: &id045
      status: unchecked
    slug: pro5
    status: queued for profiling
    tags: &id046 []
    url: null
  layer: domain
  name: Pro5
  provider: pro5
  says: lists Pro5 as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id047
      source: https://registry.modelcontextprotocol.io/v0/servers?search=io.puzzle/puzzle
      status: verified
    slug: puzzle
    status: profiled
    tags: &id048
    - Accounting
    - Bookkeeping
    - Company
    - Finance
    url: /providers/puzzle/
  layer: common
  name: Puzzle Financial
  provider: puzzle
  says: lists Puzzle Financial as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id049
      source: https://github.com/intuit/quickbooks-online-mcp-server
      status: verified
    slug: quickbooks
    status: profiled
    tags: &id050
    - Accounting
    - Bookkeeping
    - Finance
    - Small Business
    url: /providers/quickbooks/
  layer: common
  name: QuickBooks
  provider: quickbooks
  says: lists QuickBooks as an integration
  source: https://www.deel.com/integrations/
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
  layer: common
  name: Sage
  provider: sage
  says: lists Sage as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id053
      status: none
    slug: sap-successfactors
    status: profiled
    tags: &id054
    - HCM
    - Human Resources
    - Payroll
    - Talent Management
    url: /providers/sap-successfactors/
  layer: domain
  name: SAP SuccessFactors
  provider: sap-successfactors
  says: lists SAP SuccessFactors as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id057
      source: https://docs.slack.dev/ai/mcp-server/
      status: verified
    slug: slack
    status: profiled
    tags: &id058
    - Bots
    - Chat
    - Collaboration
    - Messaging
    url: /providers/slack/
  layer: common
  name: Slack
  provider: slack
  says: lists Slack as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-300.60
    key: employee-experience-management
    name: Employee Experience Management
    url: /capabilities/employee-experience-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 0.0
    band: emerging
    in_catalog: true
    kin_score: 15.7
    mcp: &id059
      status: none
    slug: snappy
    status: profiled
    tags: &id060
    - Company
    - Corporate Gifting
    - Employee Recognition
    - Human Resources
    url: /providers/snappy/
  layer: domain
  name: Snappy Gifts
  provider: snappy
  says: lists Snappy Gifts as an integration
  source: https://www.deel.com/integrations/
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
    agent_band: agent-native
    agent_readiness: 48.9
    band: strong
    in_catalog: true
    kin_score: 60.2
    mcp: &id061
      status: none
    slug: spendesk
    status: profiled
    tags: &id062
    - Corporate Cards
    - Expense Management
    - Invoices
    - Spend Management
    url: /providers/spendesk/
  layer: common
  name: Spendesk
  provider: spendesk
  says: lists Spendesk as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4330.10
    key: timekeeping-management
    name: Timekeeping Management
    url: /capabilities/timekeeping-management/
    via_parent: null
  credit: null
  facts:
    agent_band: agent-ready
    agent_readiness: 38.0
    band: emerging
    in_catalog: true
    kin_score: 22.4
    mcp: &id063
      source: https://www.timedoctor.com/mcp
      status: verified
    slug: time-doctor
    status: profiled
    tags: &id064
    - Company
    - Productivity
    - Time Tracking
    - Workforce Management
    url: /providers/time-doctor/
  layer: domain
  name: Time Doctor
  provider: time-doctor
  says: lists Time Doctor as an integration
  source: https://www.deel.com/integrations/
  tier: declared
- capability:
    attribution: Turbo EA
    id: BC-4320
    key: professional-workforce-resourcing-management
    name: Professional Workforce Resourcing Management
    url: /capabilities/professional-workforce-resourcing-management/
    via_parent: null
  credit: null
  facts:
    agent_band: human-only
    agent_readiness: 2.5
    band: minimal
    in_catalog: true
    kin_score: 8.6
    mcp: &id065
      status: none
    slug: webstarted
    status: profiled
    tags: &id066
    - Latin America
    - Nearshore
    - Recruiting
    - Staff Augmentation
    url: /providers/webstarted/
  layer: domain
  name: Webstarted
  provider: webstarted
  says: lists Webstarted as an integration
  source: https://www.deel.com/integrations/
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
    agent_readiness: 34.4
    band: strong
    in_catalog: true
    kin_score: 55.9
    mcp: &id067
      status: none
    slug: workday
    status: profiled
    tags: &id068
    - Cloud Computing
    - Enterprise Software
    - Financial Management
    - HCM
    url: /providers/workday/
  layer: domain
  name: Workday
  provider: workday
  says: lists Workday as an integration
  source: https://www.deel.com/integrations/
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
    mcp: &id069
      source: https://github.com/XeroAPI/xero-mcp-server
      status: verified
    slug: xero
    status: profiled
    tags: &id070
    - Accounting
    - Bank Feeds
    - Finance
    - Financial Services
    url: /providers/xero/
  layer: common
  name: Xero
  provider: xero
  says: lists Xero as an integration
  source: https://www.deel.com/integrations/
  tier: declared
kind: commercial
layout: application-app
license: CC BY-NC-SA 4.0
no_rows_reason: null
noindex: false
permalink: /applications/payroll-hr/deel/
providers:
- agent_band: agent-ready
  agent_readiness: 56.7
  band: strong
  in_catalog: true
  kin_score: 63.5
  mcp: *id001
  name: Amplitude
  slug: amplitude
  status: profiled
  tags: *id002
  url: /providers/amplitude/
- agent_band: agent-ready
  agent_readiness: 31.9
  band: developing
  in_catalog: true
  kin_score: 52.4
  mcp: *id003
  name: Ashby
  slug: ashby
  status: profiled
  tags: *id004
  url: /providers/ashby/
- agent_band: agent-aware
  agent_readiness: 26.8
  band: developing
  in_catalog: true
  kin_score: 40.9
  mcp: *id005
  name: BambooHR
  slug: bamboohr
  status: profiled
  tags: *id006
  url: /providers/bamboohr/
- agent_band: agent-ready
  agent_readiness: 35.1
  band: exemplar
  in_catalog: true
  kin_score: 67.2
  mcp: *id007
  name: CrowdStrike
  slug: crowdstrike
  status: profiled
  tags: *id008
  url: /providers/crowdstrike/
- agent_band: human-only
  agent_readiness: 0.0
  band: minimal
  in_catalog: true
  kin_score: 7.2
  mcp: *id009
  name: DATEV
  slug: datev
  status: profiled
  tags: *id010
  url: /providers/datev/
- agent_band: human-only
  agent_readiness: 2.5
  band: emerging
  in_catalog: true
  kin_score: 25.1
  mcp: *id011
  name: Employee Navigator
  slug: employeenavigator
  status: profiled
  tags: *id012
  url: /providers/employeenavigator/
- agent_band: agent-aware
  agent_readiness: 14.2
  band: developing
  in_catalog: true
  kin_score: 50.3
  mcp: *id013
  name: Firebase (Crashlytics / Analytics)
  slug: firebase
  status: profiled
  tags: *id014
  url: /providers/firebase/
- agent_band: agent-aware
  agent_readiness: 8.6
  band: minimal
  in_catalog: true
  kin_score: 9.5
  mcp: *id015
  name: Fizard
  slug: fizard
  status: profiled
  tags: *id016
  url: /providers/fizard/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.5
  mcp: *id017
  name: FloCareer
  slug: flocareer
  status: profiled
  tags: *id018
  url: /providers/flocareer/
- agent_band: agent-ready
  agent_readiness: 37.9
  band: exemplar
  in_catalog: true
  kin_score: 68.6
  mcp: *id019
  name: Google Workspace
  slug: google-workspace
  status: profiled
  tags: *id020
  url: /providers/google-workspace/
- agent_band: agent-ready
  agent_readiness: 58.8
  band: exemplar
  in_catalog: true
  kin_score: 79.7
  mcp: *id021
  name: Greenhouse
  slug: greenhouse
  status: profiled
  tags: *id022
  url: /providers/greenhouse/
- agent_band: agent-aware
  agent_readiness: 19.7
  band: thin
  in_catalog: true
  kin_score: 30.4
  mcp: *id023
  name: HiBob
  slug: bob
  status: profiled
  tags: *id024
  url: /providers/bob/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id025
  name: Hofy
  slug: hofy
  status: queued for profiling
  tags: *id026
  url: null
- agent_band: agent-ready
  agent_readiness: 39.7
  band: thin
  in_catalog: true
  kin_score: 33.7
  mcp: *id027
  name: Hubstaff
  slug: hubstaff
  status: profiled
  tags: *id028
  url: /providers/hubstaff/
- agent_band: agent-aware
  agent_readiness: 19.8
  band: developing
  in_catalog: true
  kin_score: 47.9
  mcp: *id029
  name: Human Interest
  slug: human-interest
  status: profiled
  tags: *id030
  url: /providers/human-interest/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 22.1
  mcp: *id031
  name: JobzMall
  slug: jobzmall
  status: profiled
  tags: *id032
  url: /providers/jobzmall/
- agent_band: agent-aware
  agent_readiness: 23.2
  band: thin
  in_catalog: true
  kin_score: 34.0
  mcp: *id033
  name: JumpCloud
  slug: jumpcloud
  status: profiled
  tags: *id034
  url: /providers/jumpcloud/
- agent_band: agent-aware
  agent_readiness: 13.7
  band: emerging
  in_catalog: true
  kin_score: 17.3
  mcp: *id035
  name: Moss (getmoss.com)
  slug: getmoss
  status: profiled
  tags: *id036
  url: /providers/getmoss/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 12.5
  mcp: *id037
  name: NetSuite
  slug: netsuite
  status: profiled
  tags: *id038
  url: /providers/netsuite/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 14.1
  mcp: *id039
  name: Pangea (contract-to-hire)
  slug: pangea-io
  status: profiled
  tags: *id040
  url: /providers/pangea-io/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 17.5
  mcp: *id041
  name: Pave
  slug: pave
  status: profiled
  tags: *id042
  url: /providers/pave/
- agent_band: agent-ready
  agent_readiness: 41.8
  band: thin
  in_catalog: true
  kin_score: 31.4
  mcp: *id043
  name: Personio
  slug: personio
  status: profiled
  tags: *id044
  url: /providers/personio/
- agent_band: null
  agent_readiness: null
  band: null
  in_catalog: false
  kin_score: null
  mcp: *id045
  name: Pro5
  slug: pro5
  status: queued for profiling
  tags: *id046
  url: null
- agent_band: agent-ready
  agent_readiness: 31.6
  band: developing
  in_catalog: true
  kin_score: 47.6
  mcp: *id047
  name: Puzzle Financial
  slug: puzzle
  status: profiled
  tags: *id048
  url: /providers/puzzle/
- agent_band: agent-native
  agent_readiness: 41.2
  band: strong
  in_catalog: true
  kin_score: 61.1
  mcp: *id049
  name: QuickBooks
  slug: quickbooks
  status: profiled
  tags: *id050
  url: /providers/quickbooks/
- agent_band: agent-ready
  agent_readiness: 31.3
  band: developing
  in_catalog: true
  kin_score: 41.8
  mcp: *id051
  name: Sage
  slug: sage
  status: profiled
  tags: *id052
  url: /providers/sage/
- agent_band: agent-aware
  agent_readiness: 24.3
  band: emerging
  in_catalog: true
  kin_score: 26.1
  mcp: *id053
  name: SAP SuccessFactors
  slug: sap-successfactors
  status: profiled
  tags: *id054
  url: /providers/sap-successfactors/
- agent_band: agent-ready
  agent_readiness: 50.2
  band: exemplar
  in_catalog: true
  kin_score: 80.6
  mcp: *id055
  name: Sentry
  slug: sentry-system
  status: profiled
  tags: *id056
  url: /providers/sentry-system/
- agent_band: agent-ready
  agent_readiness: 38.7
  band: exemplar
  in_catalog: true
  kin_score: 74.7
  mcp: *id057
  name: Slack
  slug: slack
  status: profiled
  tags: *id058
  url: /providers/slack/
- agent_band: human-only
  agent_readiness: 0.0
  band: emerging
  in_catalog: true
  kin_score: 15.7
  mcp: *id059
  name: Snappy Gifts
  slug: snappy
  status: profiled
  tags: *id060
  url: /providers/snappy/
- agent_band: agent-native
  agent_readiness: 48.9
  band: strong
  in_catalog: true
  kin_score: 60.2
  mcp: *id061
  name: Spendesk
  slug: spendesk
  status: profiled
  tags: *id062
  url: /providers/spendesk/
- agent_band: agent-ready
  agent_readiness: 38.0
  band: emerging
  in_catalog: true
  kin_score: 22.4
  mcp: *id063
  name: Time Doctor
  slug: time-doctor
  status: profiled
  tags: *id064
  url: /providers/time-doctor/
- agent_band: human-only
  agent_readiness: 2.5
  band: minimal
  in_catalog: true
  kin_score: 8.6
  mcp: *id065
  name: Webstarted
  slug: webstarted
  status: profiled
  tags: *id066
  url: /providers/webstarted/
- agent_band: agent-ready
  agent_readiness: 34.4
  band: strong
  in_catalog: true
  kin_score: 55.9
  mcp: *id067
  name: Workday
  slug: workday
  status: profiled
  tags: *id068
  url: /providers/workday/
- agent_band: agent-native
  agent_readiness: 61.3
  band: exemplar
  in_catalog: true
  kin_score: 82.4
  mcp: *id069
  name: Xero
  slug: xero
  status: profiled
  tags: *id070
  url: /providers/xero/
siblings:
- name: ADP Mobile Solutions
  rows: 5
  url: /applications/payroll-hr/adp-mobile-solutions/
- name: Connecteam
  rows: 3
  url: /applications/payroll-hr/connecteam/
- name: Frappe HR
  rows: 1
  url: /applications/payroll-hr/frappe-hr/
- name: Homebase
  rows: 19
  url: /applications/payroll-hr/homebase/
- name: Horilla
  rows: 7
  url: /applications/payroll-hr/horilla/
- name: OrangeHRM
  rows: 0
  url: /applications/payroll-hr/orangehrm/
- name: Paylocity
  rows: 4
  url: /applications/payroll-hr/paylocity/
- name: Workday
  rows: 2
  url: /applications/payroll-hr/workday/
sitemap: true
title: 'Deel: HR, Payroll & People Ops reference app'
---
